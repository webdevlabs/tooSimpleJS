# tooSimpleJS
very simple javascript framework

**Features:**
- selectors
- html content changer
- css style changer
- events
- hide, show, toggle

### Usage
***
$$('#someID').html('some html content');

$$('.someClass').css('display:none');

$$('#thisInput').on('change', function () {
  alert('input changed');
});

$$('#thisInputbtn').on('click', function () {
  alert('button clicked');
});

$$('input[name="test"]').show();

$$('input[name="test"]').hide();

$$('input[name="test"]').toggle();

***
