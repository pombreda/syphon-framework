## Introduction ##

Public Beta 2 improves server discovery and removal, allows a server access to its own output, and includes fixes for some minor issues.

### Changes ###

  * Improve removal of servers if a remote application with servers hangs or crashes ([r4](https://code.google.com/p/syphon-framework/source/detail?r=4))
  * Fix a potential lock conflict when stopping clients ([r8](https://code.google.com/p/syphon-framework/source/detail?r=8), [r11](https://code.google.com/p/syphon-framework/source/detail?r=11))
  * Add - newFrameImage method to SyphonServer ([r10](https://code.google.com/p/syphon-framework/source/detail?r=10))
  * Fix issue where one frame of garbage was sometimes sent to its first client if a server used - hasClients to conditionally draw ([r26](https://code.google.com/p/syphon-framework/source/detail?r=26))
  * Fix issue which affected publishing a GL\_TEXTURE\_2D texture with no mipmaps ([r27](https://code.google.com/p/syphon-framework/source/detail?r=27))
  * Make the Syphon icon available for use by applications ([r29](https://code.google.com/p/syphon-framework/source/detail?r=29))
  * Fix issue which delayed server discovery in some versions of MacOS X ([r30](https://code.google.com/p/syphon-framework/source/detail?r=30), [r37](https://code.google.com/p/syphon-framework/source/detail?r=37))
  * If an application fails to stop servers programmatically, they are stopped by the framework when the application quits ([r45](https://code.google.com/p/syphon-framework/source/detail?r=45))
  * Code cleanup ([r6](https://code.google.com/p/syphon-framework/source/detail?r=6), [r7](https://code.google.com/p/syphon-framework/source/detail?r=7), [r9](https://code.google.com/p/syphon-framework/source/detail?r=9), [r12](https://code.google.com/p/syphon-framework/source/detail?r=12), [r28](https://code.google.com/p/syphon-framework/source/detail?r=28), [r40](https://code.google.com/p/syphon-framework/source/detail?r=40), [r42](https://code.google.com/p/syphon-framework/source/detail?r=42))