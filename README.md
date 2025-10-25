# Adaptive Memory Network
An active, evolving memory system for Claude Projects. File-based (manual) or Edit-based (automatic).

## File-based (Claude Memory OFF)
This is the natural way of using AMN: an extended memory without limitations.
This approach is used when the Claude Memory feature is not active.
You will have to upload the amn_base.xml and subsequent updates to the Project files.

## Edit-based (Claude Memory ON)
This is the AMN adapted to the native Claude Memory feature. Claude manages its memory automatically.
The Claude Memory feature must be enabled in Settings > Capabilites.
This was a recent addition to the original AMN: though limited in capacity (30 edits, 200 characters/edit, 6KB total), we saw a valuable opportunity to automate the AMN. This is an early stage experiment.

## Quick start
1. Turn the Claude Memory feature ON or OFF in Settings > Capabilities
2. Create a new Claude Project
3. Copy/Paste the amn_v0.3.md content in the Project Instructions
4. Start a conversation

For the file-based approach, the first conversation should produce the base_amn.xml file to upload in the Project Files. The following conversations should produce amn_update_NNN.xml files to add to the Project Files.

For the edit-based approach, Claude should automatically update its Memory when needed.
