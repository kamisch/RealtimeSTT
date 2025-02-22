## v0.4.0 (2025-02-22)

### Feat

- add init_logging option to allow users to use their own logging framework
- reduce realtime transcription load by only transcribing if new frames arrive

### Fix

- wrong arguments for self.stream.read
- make sure shutdown() wakes up the recording_thread
- clear text storage and audio frames on audio queue clear
- add webrtc that does not need visual studio to build

### Refactor

- remove unneeded import
