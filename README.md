# RL78-RFD-EES
Sample Projects and Builds for RL78 using provided flash routines of RFD &amp; EES

SampleEES-Orig.7z - Build using original v1.0 provided RFD / EES source code for G23 device (CC-RL & IAR v4)

SampleEES-EraseCounter-BkgdRefresh.7z - Build using EES modified to add virtual block-header Erase Counter and add Background Refresh capability (CC-RL & IAR v4)

Note - RFD for G23 device is missing internal verify function to check if all bits provide full data retention.
       Absent this capability, inconsistent and weak data caused by asychronous reset during a write
       command cannot be detected.  This capability was provided for all (Std/T01, Tiny/T02, Pico/T04) RL78 FDL
       libraries.
