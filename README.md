# PaulsTrampoline
planning notes etc for a demonstrator

## Background on a Paul Trap (RF quadrupole trap)
A nice website with the basics, and the details, and a build outline for a different but related thing. https://aquadrupauliontrap.wordpress.com/background/

## The challenge
In physics-speak: *how do we create an electric potential with a minimum at the centre of an empty volume of space?*

In plain terms: *how do we force our thing to want to go to the middle, without touching the middle at all?* Gravity is great at making stuff go to the edge (the floor), centripetal force can also make stuff go to the edge.

In terms of a trampoline: *How do we made a depression at the center of a trampoline by only manipulating the edges?* Then a ball will just roll to the centre. Its a bit tricky to avoid the apparently obvious solution of using a heavy ball to "just create the depression that it sits in", but that is cheating! - since that sort of depression wouldn't be there without the heavy ball being there (manipulating the center). So we have to think about working with a light ball, and a stiff trampoline.

## The answer
...Is to either rotate a saddle (or pringle) shaped surface\* around a center vertical axis, or to waggle or oscillate a saddle (or pringle) shaped surface, inverting the upward curved bits to downward curved bits repeatedly.

![image](https://github.com/user-attachments/assets/6725fc32-d399-4cd2-b580-19abb9fbbf8f)

Rotating has been done many times as a teaching demo - eg https://www.youtube.com/watch?v=XTJznUkAmIY

Waggling is a much more accurate description of what we do in real experiments on quantum particles.

\* It turns out that you can form a trampoline into a saddle shape by only touching the outside edge. Not possible for a valley or a hill type shape (hopefully thats self evident).


## Similar trampoline-based demo for inspiration
To illustrate gravitational waves, a trampoline arrangement with excitation in the center, and the "field" propagating outwards: https://www.youtube.com/watch?v=dw7U3BYMs4U

![image](https://github.com/user-attachments/assets/3612e910-131d-406e-8451-a0da837cf1df)

Our objective is a bit similar, but the excitation is on the outside edges, the "field" propagating inward dynamically to create the configuration capable of confining a ball.

## The device

- A rubber sheet, or some thick elastic fabric maybe. some trial end error likely needed to find a good stiffness and tension combination [example rubber material](https://rubberfast.co.uk/products/para-shotblast-rubber-sheet?variant=47618026307864)
- Linear actuators x4 (likely the reciprocating cycle type, or the very fast end of geared stepper motor type, or voice coil type) *cams and gears with a variable speed elecrtic motor is fine*
- Clamps x4 (should be hyperbola shaped for optimal excitation)

![image](https://github.com/user-attachments/assets/46bc6505-7bfe-4707-bfe1-06f216eb009b)

- A frame / chassis, sturdy and robust, keeping all the hasardous parts away from fingers
- A control knob for the speed (frequency)
- optionally also a speed readout
- A collection of balls to test, different masses is interesting (optimal size has to be worked out)
- safety? proximity sensor cutout if there are pinch point hazards


