Panoramix  ====
===== This is an 
EVM decompiler.
It 
is a fork of the Panoramix 
original repo that's not maintained
actively by author  https://github.com/eveem-org/panoramix.git
so https://github.com/Apetree333/panoramix has made some changes 
The goal of this fork is to
fix some crashes, implement missing 
opcodes as well as correct redundancy
And I am going to try and include multiple versions.
finally, with your comments we can make this a great decompiler
the software is complex nothing that can not be Simplified
#
# Installation
```console
$ pip install panoramix-decompiler
``` # # Running You can specify a
web3 provider using the environment
variable `WEB3_PROVIDER_URI` ```console
$ WEB3_PROVIDER_URI:
http://localhost:7545
panoramix 0x0d94D81FD71
2126E7f320b5B10537D01d6a01563
``` You can also provide the bytecode
for decompilation ```console $ panoramix
6004600d60003960046000f30011223344```
#
# Examples I have decompiled all of
mainnet,
and make sure
to decompile again on the latest
 Panoramix version from time to time.
You can access decompilations
using Oko:
 https://oko.palkeo.com/  <or from this
14.15.0 <https://github.com/Apetree333/panoramix>
 an example for
cryptokitties: https://oko.palkeo.com
/0x06012c8cf97BEaD5deAe
237070F9587f8E7A266d
/  code  /  #
  #  Caveats 
#   # Change
  log
# # # beta  * Added support for the
 BASEFEE opcode. * Updated bytecode database
 / ABI definitions. * Ability to decompile
 the Solidity-generated Panic reverts.* Lots of
simplification  [ have not noticed  will point out follow changes]
 / code cleanup * Moved to Poetry as
the dependency management tool
date of changes 2024 02 09
@ 0430 pst 
