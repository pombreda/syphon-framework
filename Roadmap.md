# Introduction #

  * Merge Garagecube Private Branch with Float Texture Support branch.
  * Finish Float Texture Support
  * OpenGL 3.2 Support.
  * Handle Application Sandboxing / IPC issues.
  * Network support.

# Details #

  * Merge Garagecube branch (public-beta-2-gc) (MSAA, Depth Buffer, Stencil Buffer) with trunk

  * Finish Float Texture Support - need to explore compatibility, especially for situations where multiple GPUs are involved. This is similar to the MSAA case above. [issue 13](https://code.google.com/p/syphon-framework/issues/detail?id=13)

  * OpenGL 3.2 Support. [issue 22](https://code.google.com/p/syphon-framework/issues/detail?id=22)

  * Handle Application Sandboxing / IPC issues. Possible workarounds for Announcement / Discovery via Bonjour/Rendezvous - See [issue 20](https://code.google.com/p/syphon-framework/issues/detail?id=20)

  * Network support. Currently functional in private branch. Need to optimize. I think goal should be 1080p at 30. [issue 21](https://code.google.com/p/syphon-framework/issues/detail?id=21)