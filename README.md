# ConfiguratorModelD
A easy configurator for Behringer Model D.

This little app helps to configure the Behringer Model D. This synth can be setup by some MIDI sysex messages, which are more or less hard to create. So I started to implement this little GUI, which uses QMidi (and this uses rtMidi). So everybody can setup the Model D by some simple clicks...

<table>
  <tr><th colspan="2">Screenshots</th></tr>
  <tr><th>macOS</th><th>Windows</th></tr>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/30245296/35990458-5b5239e6-0d04-11e8-91c5-499e85d445c5.png" title="screenshot on macOS" /></td>
    <td><img src="https://user-images.githubusercontent.com/30245296/36419291-c2a1ef98-1631-11e8-8065-0dfd096c051e.png" title="screenshot on Windows" /></td>
  </tr>
</table>

## Usage
Open the tool, make sure the Port is "MODEL D", change the values as you like. Note: the values can only be written and not loaded from the Model D. So the initial setup shown by the app might not be the one in your synth!

## Download
Download a release [here](https://github.com/masc4ii/ConfiguratorModelD/releases).

## Compile
The app can be compiled for Windows, Linux and macOS. You just need Qt5.6 or newer. Open the ConfiguratorModelD.pro file in QtCreator, press the Run button and have fun!
