# @giantpaper/animate.scss

This is my own version of [Animate.css](http://daneden.github.io/animate.css/), converted to SASS/SCSS. Yes, there are about a billion of these out there, but I haven't found one that's been updated along with Animate.css. This one is converted with a PHP script, so it's just a literal SASS version, with no added animations or extra features.

## Installation

Install with npm

    npm install @giantpaper/animate.scss

## Usage

In your .scss file, import the animate.scss file like so:

    @import 'animate.scss';

(Obviously, update the relative path to make sure you're pointing to the actual file.)

If you want to include only certain animations:

    // Required
    @import 'vars';
  
    .animate {
      // Required
      @import 'base';
  
      // Add in the animations you want
      @import 'fading_entrance/fadeIn';
      ... // Add other @import statements for animations
    }

## License

Animate.scss is licensed under the MIT license. <https://opensource.org/licenses/MIT>
