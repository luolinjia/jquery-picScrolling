###Usage

Below is HTML and calling the widget.

    <div id="testBox">
        <img src="img/1.jpg"/>
        <img src="img/2.jpg"/>
        <img src="img/3.jpg"/>
        <img src="img/4.jpg"/>
    </div>

    $('#testBox').picScroll({
        size: {'height': '300px', width: '800px'}, // show the img size, this is required.
        color: '#999',  // the navigation color
        hovercolor: '#fff',   // the navigation hovercolor
        time: 2000,  // the time every scrolling
        hasNumber: false  // whether showing number, the default value is false
    });
