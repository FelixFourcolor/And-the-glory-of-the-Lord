# And the glory of the Lord
"And the glory of the Lord" in Handel's Messiah, arranged for Minecraft's noteblocks.

Recording: https://youtu.be/rgFYDXaD4A0

## Arrangement
Instrumentation:
* Soprano: pling + flute
* Alto: pling
* Tenor: guitar
* Bass: guitar
* Violin I: bell + flute
* Violin II: bit + harp
* Viola: harp
* Cello: bass + guitar

Tranposed down 3 semitones to better fit noteblock's ranges. However, a few notes still do not fit, then they are either transposed up/down an octave or played by a different instrument, depending on which sounds better to me.

## Play requirements
Minecraft Java 1.20+ to play the pre-built world; 1.19+ if you build from source.

Go to Music & Sounds settings and turn on Directional Audio. Optionally, turn down Master Volume to about 60% to 70%, otherwise it might be a bit too loud (but of course this depends on your speakers).

## Easy install 
Copy the [World](https://github.com/FelixFourcolor/And-the-glory-of-the-Lord/tree/main/World) folder into your saves.

To obtain the folder, you may clone the repo or use third-party tools such as [Down-Git](https://minhaskamal.github.io/DownGit) to download it.

## Build from source
### Build requirements
* python 3.10-3.12
* pip

### Overview of the build process
The structure is auto-generated using [noteblock-generator](https://pypi.org/project/noteblock-generator/). The program takes [src](https://github.com/FelixFourcolor/And-the-glory-of-the-Lord/tree/main/src) which defines the composition, and generates the structure inside an existing Minecraft world.

### Step-by-step guide

1. Install the lastest version of [noteblock-generator](https://pypi.org/project/noteblock-generator/):
    ```
    pip install --upgrade noteblock-generator
    ```
    Configure your PATH so that `noteblock-generator` is executable on the command line.

2. Obtain [src](https://github.com/FelixFourcolor/And-the-glory-of-the-Lord/tree/main/src). You may clone the repo or download just that folder.

3. Obtain a world in Minecraft Java 1.19+. You may use your existing world or create a new one.

4. Run:
    ```
    noteblock-generator [path to src] [path to minecraft world]
    ```

    See [noteblock-generator](https://pypi.org/project/noteblock-generator/) for more build options.
