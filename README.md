# XML MIDI Device Descriptions

MIDI controllers and the devices they control are amazing, but it's often hard to tell what's going on.  The MIDI protocol establishes a sophisticated way for devices to communicate with numbers, but figuring out what's happening gets complicated fast.  The manuals for MIDI devices usually specify lists of the data going in and out, how it is structured, and what it means.  However, features often go unnoticed, and integration is usually partial.

This repository defines a format for sharing information about MIDI devices using an XML vocabulary.  The format combines information programs need (channels, CC numbers, etc.) with information that humans can interpret to label and document what's happening.  Computers can also use those labels to create more inviting interfaces.  Because the data is open, people should be able to customize it for their own needs, transform it to other forms, and create their own applications around it.

Right now, I'm prototyping the markup using some common controllers, instruments, effects pedals, and other devices.  In the long run it would be wonderful if manufacturers provided this information, but prototyping and sharing first seems important.
