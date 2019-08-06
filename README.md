# strolch-wc-paging
Strolch WebComponent Paging Component

## Usage:

Import declaration:

    <!-- Import -->
    <link rel="import" href="../../../bower_components/strolch-wc-paging/strolch-wc-paging.html">

Styling:

    <!-- Style -->
    <style is="custom-style" include="strolch-wc-styles">
        ...
        strolch-wc-paging {
            max-width: 1080px;
            width: 100%;
        }

    </style>

Element:

    <!-- The paging element -->
    <strolch-wc-paging id="paging" data-obj="{{dataObj}}"></strolch-wc-paging>

JavaScript:

    /* Lifecycle */
    attached: function () {
        this.$.paging.ajax = this.$.ajaxRequestObject;
    },
