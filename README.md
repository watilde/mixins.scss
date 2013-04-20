# How to Use?

1. Import it.

        @import "mixins.scss";


2. Add Keyframes

        @include keyframes(spin) {
            0%   { @include transform(rotateX(0) rotateY(0) rotateZ(0)); }
            50%  { @include transform(rotateX(150deg) rotateY(-180deg) rotateZ(120deg)); }
            100% { @include transform(rotateX(0) rotateY(-360deg) rotateZ(0));
            }
        }


3. Call Keyframes with Animation

        @include animation(spin, infinite, linear, 10s, 0s);


:D