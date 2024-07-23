# slime-hunter-audio
The audio for Slime Hunter.

## Installation

Clone the Repository:

   ```bash
   git clone https://github.com/Studio-Bounce/slime-hunter.git
   ```

## Making Audio Changes to Slime Hunter

1. In [FMOD Studio](https://www.fmod.com/download#fmodstudio) open your `.fspro` project. 

2. Run a build with either `F7` or `File > Build`.

3. Copy the contents of `/Build/` and dump it into `slime-hunter/Assets/Game/Audio/FMOD/Build/`.

  > Alternatively you can set your build location to automatically build to the correct directory by heading to `Edit > Preferences > Build > Built banks output directory`

4. Unity should recompile with the new audio banks.
