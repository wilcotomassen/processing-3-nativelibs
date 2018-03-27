
# Processing Native Libraries

This repository contains the native libraries that are required to run a Processing
application, when you've built it (or are developing it) in an IDE that is not the
Processing IDE. They are stored here so they are available, updateable and stored, 
but don't bloat up application repositories.

# Versions of native libraries

All native libraries that come with the Processing installation came from
[Processing Release 3.2.3](https://github.com/processing/processing/releases/tag/processing-0255-3.2.3). They were all copied from /modes/java/libraries/<component>/library to the native libs in this repo.

One notable exception are the native libraries that come with Video library for Processing (Gstreamer, LibGio); they were taken directly from the (https://github.com/processing/processing-video/commit/6c7e07bc612fc6d5f3e129841638a0573f46dc2a)[latest stable version at the moment]. 
