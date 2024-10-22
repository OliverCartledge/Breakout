# Breakout

W Kavanagh. June Summer 2024

## controls

A/D to move the paddle right and left.
P to pause.

## Powerups

big/small paddle (blue)
fast/slow ball (fancy yellow)
fire ball (green)

# Tasklist

## Suggested fixes

* Fix the compiler issues in the code

## Suggested tasks

* Implement mouse input for pad
* Improved VFX (ball trail, paddle hit response, brick particle destruction)
* Better UI (progress bar rather than timer for countdown).
* GameLoop
* Better ball physics (Box2D)
* Leaderboards
* More ball types (e.g., multiball, sticky ball [where you shoot the ball from the paddle every time], tiny ball, big ball, brick-tracking ball)
* Sounds with increasing tone between bounces.
* Implement commentary with calls to an LLM such as LLama

# Time Details and Changelist
<Add information to this section about the time you've taken for this task along with a professional changelist.>
Hour 1:
- Fixed compiling error by removing include 
- Implemented SFML particle system and set up particle to enable on collision
Hour 2: 
- Changed speed power up to also include a speed boost for the paddle itself 
- Added restart functionality
- Fixed error where lives didn't reinitialize on restart
Hour 3:
- Adjusted particle system to begin in the center of the cube hit rather than the impact point
Hour 4: 
- Implemented camera shake when player loses a life
