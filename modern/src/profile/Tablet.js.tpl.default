Ext.define('{appName}.profile.Tablet', {
    extend: 'Ext.app.Profile',

    requires: [
        '{appName}.view.tablet.*'
    ],

    // Map tablet/desktop profile views to generic xtype aliases:
    //
    views: {
        email: '{appName}.view.tablet.email.Email',
        inbox: '{appName}.view.tablet.email.Inbox',
        compose: '{appName}.view.tablet.email.Compose',

        searchusers: '{appName}.view.tablet.search.Users'
    },

    isActive: function () {
        return !Ext.platformTags.phone;
    }
});
