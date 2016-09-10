BozSlider
=========

This is just a simple wrapper around the standard HTML5 range input that adds a minimum value and a label. To use, create an instance of the BozSlider, passing in the parameters you would like:

    var bozSlider = new BozSlider({
        parentElement: containerElement,
        min: 1,
        max: 9,
        step: 1,
        value: theInitialValue,
        label: "My Special Value",
        onchange: theHandlerFunction
    })

Since this is presented as a CommonJS module, you'll want to use a library that loads such modules in the browser, such as [http://browserify.org/](Browserify).