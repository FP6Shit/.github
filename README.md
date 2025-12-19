Copy and paste the following XML code to .repo/local_manifests/fairphone_FP6.xml


```<manifest>
    <remote
        name="fp6"
        fetch="https://github.com/"
        review="github.com" />
    <remote
        name="vendor"
        fetch="https://git.mainlining.org"
        review="git.mainlining.org" />    
    <remove-project path="hardware/interfaces" />

    <project
        name="FP6Shit/hardware_interfaces"
        path="hardware/interfaces"
        remote="fp6"
        revision="lineage-23.0" />
    <project 
        name="FP6Shit/device_fairphone_FP6"
        path="device/fairphone/FP6"
        remote="fp6"
        revision="23.1" />
    <project 
        name="FP6Shit/android_kernel_fairphone_sm7635"
        path="kernel/fairphone/sm7635"
        remote="fp6"
        revision="lineage-23.0" 
        clone-depth="1"/>
    <project
       name="FP6Shit/android_kernel_fairphone_sm7635-modules"
       path="kernel/fairphone/sm7635-modules"
       remote="fp6"
       revision="lineage-23.0" />
    <project
       name="FP6Shit/android_kernel_fairphone_sm7635-devicetrees"
       path="kernel/fairphone/sm7635-devicetrees"
       remote="fp6"
       revision="lineage-23.0" />
    <project 
        name="proprietary_vendor_fairphone_FP6"
        path="vendor/fairphone/FP6"
        remote="vendor"
        revision="lineage-23.0" 
        clone-depth="1"/>
</manifest>
```
