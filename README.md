# BedrockX

BedrockX is a heavily optimized version of the [Bedrock-Protocol](https://github.com/PrismarineJS/bedrock-protocol) library made by [PrismarineJS](https://github.com/PrismarineJS).

There is a example provided. You can read the source code to learn how it works.

Parts of NETHERNET Support is based off of Atomic Protocol (Original Repository now deleted) by [Serial-V](https://github.com/Serial-V)

forked from thejfkvis 

This modified version of BedrockX has the jose assertion layer removed from the Nethernet client. I downgraded the SDP handling to use raw offers without certificate signing. Also cleaned up some connection logic to make Nethernet connections more stable.
