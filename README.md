[![npm](https://img.shields.io/npm/v/nativescript-accessibility.svg)](https://www.npmjs.com/package/nativescript-accessibility)
[![npm](https://img.shields.io/npm/l/nativescript-accessibility.svg)](https://www.npmjs.com/package/nativescript-accessibility)
[![npm](https://img.shields.io/npm/dt/nativescript-accessibility.svg?label=npm%20d%2fls)](https://www.npmjs.com/package/nativescript-accessibility)

# nativescript-accessibility
Add full accessibility to the NativeScript framework

**WARNING:** The code is NOT on NPM yet, the code is only available to Patreon supporters.
THIS is on NPM to be used as a Placeholder so that this plugin does have a home when it is finally released.

## License

The actual code is released under what I call the PATRON License, meaning you are free to include this in any type of program as long as you downloaded this when you were a current patron and/or sponsor, and got the file directly from my patreon post.  It will be released under a proper open source license at a time of my choosing (typically after a couple months of exclusive access by sponsor's).  At that point the product will be re-released under the MIT license. -- However for entities that need a support contract, changes, enhancements and/or a commercial license please contact me at [http://nativescript.tools](http://nativescript.tools).

I also do contract work; so if you have a module you want built for NativeScript (or any other softw

[![Donate](https://img.shields.io/badge/Donate-PayPal-brightgreen.svg?style=plastic)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=HN8DDMWVGBNQL&lc=US&item_name=Nathanael%20Anderson&item_number=nativescript%2daccessibility&no_note=1&no_shipping=1&currency_code=USD&bn=PP%2dDonationsBF%3ax%3aNonHosted)
[![Patreon](https://img.shields.io/badge/Pledge-Patreon-brightgreen.svg?style=plastic)](https://www.patreon.com/NathanaelA)


## Installation

Download from the patreon link

tns plugin add nativescript-accessibility-1.0.0.tgz


## Usage

To use the  module you just `require()` it:

```js
require( "nativescript-accessibility" );
```

Notice: You do NOT need to keep a reference to it; and you only need to load it once.  
It will automatically attach its methods to all the proper classes in the NativeScript library making it act as if they are built in.

### XML/Declarative ui access
<Image accessibilityText="Describe Image" accessibilityHidden="true">

 
### Properties

#### accessibilityText (String = defaults to not set)
This is the text for a screen reader to read (or other accessibility device)

```js
  someViewElement.accessibilityText = "A Screen reader will read this text.";
```

#### accessibilityHidden (Boolean = defaults to false)
This allows you to hide this object from a accessibility device

```js
  someViewElement.accessibilityHidden = true;
```

