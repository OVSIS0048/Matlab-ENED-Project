# MATLAB ENED Project

A MATLAB App Designer project combining a pothole-avoidance car game with a physics calculator for estimating material fatigue life using Basquin’s equation.

## Features

- **Pothole car game:** Steer a car left and right along the horizontal (x) axis while potholes slide down from the top of the screen.
- **Physics calculator:** Calculate material-related fatigue information using Basquin’s equation.
- **App interface:** MATLAB App Designer applications provide the project’s interface.

## Requirements

- MATLAB with App Designer support.
- The project’s `.mlapp` and supporting files available in the same folder.

## Run the project

1. Clone or download this repository and open the project folder in MATLAB.
2. Open `SplashScreen.mlapp` in App Designer and run it to launch the app.
3. If you want to open the game directly, open and run `CarGame.mlapp` instead.

Keep the supplied image and data files in the project folder so the apps can find their resources.

## Basquin’s equation

Basquin’s equation describes the relationship between cyclic stress amplitude and fatigue life in the high-cycle fatigue regime. A commonly used form is:

\[
\sigma_a = \sigma'_f (2N_f)^b
\]

where:

- \(\sigma_a\) is the stress amplitude,
- \(\sigma'_f\) is the fatigue strength coefficient for the material,
- \(N_f\) is the number of cycles to failure, and
- \(b\) is the fatigue strength exponent.

Use consistent units and the material constants expected by the calculator. The calculator’s available inputs and outputs are defined by the app implementation.

## Project files

| File | Description |
| --- | --- |
| `SplashScreen.mlapp` | App Designer splash screen / app entry point. |
| `CarGame.mlapp` | App Designer car game. |
| `CarIcon.png`, `CarSprite.png` | Car image assets. |
| `platlab.mat` | MATLAB data file used by the project. |

## License

See [LICENSE](LICENSE) for license information.
