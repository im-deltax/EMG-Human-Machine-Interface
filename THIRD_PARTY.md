# Third-party design-library sources

Standard symbols and footprints: KiCad community libraries distributed with the official KiCad 9.0.7 release. Libraries are CC-BY-SA 4.0 with the KiCad electronic-design exception; see `LICENSE_KiCad_Libraries.md` and https://www.kicad.org/libraries/license/ .

Project-local derivatives: stock symbols R, C, C_Polarized, ADS1299, PWR_FLAG, Q_PMOS, Q_NPN, D_Dual_Series_AKC. PMOS/NPN pins were assigned numeric manufacturer pad numbers, and project symbols were renamed. Stock resistor/capacitor/package/connector/testpoint footprints were renamed; external 3D model paths were removed. Stock-derived library material retains the KiCad library license.

Seeed Studio XIAO nRF52840 SMD footprint: https://files.seeedstudio.com/wiki/XIAO-KiCad-Library/New_XIAO_Series_Footprints.zip , obtained through https://wiki.seeedstudio.com/XIAO_BLE/ . XIAO-nRF52840-SMD was renamed into EMG8_FP; geometry and pad numbering retained, external 3D references removed. The source zip did not contain a separate license file; retain this attribution and consult Seeed's applicable terms for redistribution beyond this project. The custom schematic symbol follows the official numeric pad map.

Acquisition date: 2026-10-03. No KiCad executable, installer, manufacturer datasheet PDF or external 3D model is included in the delivered project zip.


Independent A additions: BSS138BK symbol derived from KiCad9 Device:Q_NMOS, numeric pins from Nexperia datasheet. TXU0304PW custom symbol numeric pin/direction data from TI SCES935A; footprint from KiCad9 TSSOP-14_4.4x5mm_P0.65mm, project-local copy. No additional library waiver or model dependency.

C26 proposed KEMET T491B226K010AT manufacturer specifications: https://yageogroup.com/download/specsheet/T491B226K010AT . Only the part identifier and source link are included; no manufacturer datasheet is redistributed.
