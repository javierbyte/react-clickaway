# React Clickaway

Mixin that adds a `componentClickAway` method to react components that fires the you click away from it.

## Installation

    npm install react-clickaway --save

Add it to your component

    mixins: [
        require('react-clickaway')
    ]

And then just add the method:

    componentClickAway: function() {
        console.log('Someone clicked outside this component...')
    }

## Thanks
This is just a modularized version of the https://github.com/callemall work, they used this script internally on material-ui.
