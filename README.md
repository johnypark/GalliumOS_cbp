# GalliumOS_cbp
Repo for describing galliumOS installation in cbp. 
https://chrx.org/

### Getting started: from https://wiki.galliumos.org/Hardware_Compatibility#cite_note-chrx-12
The specification of cbp: 
- Model: Samsung Chromebook Pro (XE510C24) 
- Hardware ID, Released: CAROLINE 	2017
Hardware ID: Each Chromebook/box/base model is identified by a hardware ID. Some manufacturers reuse model names for different hardware IDs (e.g. Samsung), and others market several versions of the same hardware ID (e.g. HP). For purposes of support questions, hardware ID is the most important identifier for your model. You can check your Hardware ID from the Developer Mode boot screen ("OS verification is OFF"), from the Terminal (dmidecode -s system-product-name) or from inside ChromeOS by navigating to chrome://system, where it's called hardware_class.
- Processor: Intel Skylake; Skylake models are mostly supported. See https://github.com/GalliumOS/galliumos-distro/issues/274
- Supported by GalliumOS? Yes
- with factory firmware?[13] Yes, with issues
- dual-boot with ChromeOS?[12] Yes Known 
	 	Intel Skylake[8] 	Yes 	Yes, with issues: boot video 	Yes 	Yes[12] 	internal audio[8]
    
#firmware issues
Skylake
        CHELL, others?: Stock Legacy boot support functional, but video resolution sub-optimal, screen redraws slow.
            fixed in custom firmware: MrChromebox (RW_LEGACY)
