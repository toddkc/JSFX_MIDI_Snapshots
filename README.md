# JSFX_MIDI_Snapshots
Configurable MIDI message output from a single MIDI note input.

https://user-images.githubusercontent.com/30729865/158197281-bbc1338d-30bb-4628-9e74-23411a286bcb.png

Note that this plugin relies on https://github.com/geraintluff/jsfx-ui-lib <br>
This must be installed with the plugin (I am researching if I can include it with mine for ease of use).

After attempting to use Archetype: Petrucci with my band and experimenting with various MIDI setups using my FCB1010 I was doing some research and found out about Snapshots from the Line 6 Helix products.  They have three distinct ways of controlling with footswitches.  Preset Mode will switch to whatever preset is assigned to that footswitch.  Stompbox Mode will toggle an effect on/off when the footswitch is pressed.  Snapshots will toggle any number of settings within the preset.

In a cover band with only presets you will likely end up with hundreds of presets.  Each song you do may have several.  Storing all these presets and remembering how your pedalboard is setup is frustrating.  Ideally one song would be one preset.  Stompbox mode is great but at least for me I can never seem to do some of the more complex switches correctly in the time desired.  Going from a clean tone with compressor, chorus, and reverb, to a solo tone with overdrive and delay?  That's a lot of button presses.

Snapshots solve this problem.  You have your "preset" pedalboard, and each snapshot within that preset stores which amp and effects you want.  Snapshot 1 may be the intro, Snapshot 2 the verse, Snapshot 3 the chorus, etc.  Neural DSP plugins do not have this feature built-in but with Reaper I was able to make a simplified version of it.

Using Reaper you can load a track with Archetype: Petrucci and create your song preset.  Make sure that preset has the included MIDI config.  Add another track for your MIDI pedalboard input and route the output to the Archetype track.  Add this plugin to the MIDI track.  Setup however many snapshots you need and save that as a preset for your song.  For bonus points you can save both tracks with their effect setups as a preset also so you could use it more easily across Reaper projects.
