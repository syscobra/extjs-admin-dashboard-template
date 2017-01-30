Ext.define('{appName}.view.charts.ChartsModel', {
    extend: 'Ext.app.ViewModel',
    alias: 'viewmodel.charts',

    stores: {
        barData: {
            model: '{appName}.model.DataXY',
            autoLoad: true,

            proxy: {
                type: 'api',
                url: '~api/marketshare/oneyear'
            }
        },

        stackedData: {
            model: '{appName}.model.MultiDataXY',
            autoLoad: true,

            proxy: {
                type: 'api',
                url: '~api/marketshare/multiyear'
            }
        },

        gaugeData: {
            data: [
                {
                    position: 40
                }
            ],

            fields: [
                {
                    name: 'position'
                }
            ]
        },

        radialData: {
            model: '{appName}.model.DataXY',
            autoLoad: true,

            proxy: {
                type: 'api',
                url: '~api/radial'
            }
        },

        lineData: {
            model: '{appName}.model.DataXY',
            autoLoad: true,

            proxy: {
                type: 'api',
                url: '~api/marketshare/oneentity'
            }
        },

        pieData: {
            model: '{appName}.model.DataXY',
            autoLoad: true,

            proxy: {
                type: 'api',
                url: '~api/pie'
            }
        },

        areaData: {
            model: '{appName}.model.MultiDataXY',
            autoLoad: true,

            proxy: {
                type: 'api',
                url: '~api/dashboard/full'
            }
        }
    }
});
