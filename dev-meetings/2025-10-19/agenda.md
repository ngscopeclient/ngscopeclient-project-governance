# Developer meeting agenda 2025-10-19

## 0.1.1 maintenance release

Aiming for end of month to early November. Focus is fixing major usability and packaging issues discovered after the 0.1 launch.

Fixed a couple of bugs, finally got rid of FFTS in unit tests, updated thunderscope interface

## 0.2 plans

* Make filter graph bidirectionally traversable
* Make filters and instrument channels shared_ptr's
* Make enable/disable channel done based on loads of the channel (or trigger, this is instrument dependent)
* Make CDR output sampled data + optional clock
