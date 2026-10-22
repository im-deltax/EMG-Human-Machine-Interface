# EMG Human–Machine Interface

An eight-channel EMG hardware research project by Trần Minh Triết (im-deltax), intended to explore assistive human–computer interaction for people with disabilities using muscle signals.

## PCB-only publication

This repository contains the existing `EMG8_Wireless.kicad_pcb`, its KiCad project settings, and the project-local footprint library required for editing. Open the PCB with KiCad 9. The schematic, datasets, AI training code, simulations, backups and unrelated files are intentionally not included in this PCB-only publication. PCB filename and geometry are unchanged from the supplied source.

The intended assistive interaction features are development goals, not demonstrated outcomes of this release. Firmware, a working computer-control application and user-study results are not included.

## Verification status

The supplied historical `DRC_RevB_final.rpt` reports 10 warning-level violations, 0 unconnected pads and 0 footprint errors. That report is not a fresh check of this publication, and DRC has not been rerun here. Other historical documents describe different design revisions; their release-ready claims are not adopted by this repository.

No fabrication, electrical bring-up, human-use safety validation or assistive-performance validation is established by this publication. This is a research design, not a certified medical device. The supplied source notes shared USB ground and unverified isolation; do not infer suitability for connecting electrodes to a person from these files.

## Licensing and attribution

No new blanket license is assigned to the author's PCB design in this publication. The license selected for Robodeltax does not automatically apply to this separate project. Third-party library notices are retained in [THIRD_PARTY.md](THIRD_PARTY.md) and [LICENSE_KiCad_Libraries.md](LICENSE_KiCad_Libraries.md). These files describe library sources; their inclusion does not imply the full original schematic or every referenced component is included here.

## Tiếng Việt

Dự án nghiên cứu thiết bị EMG tám kênh nhằm hỗ trợ người khuyết tật tương tác với máy tính bằng tín hiệu cơ. Bản này chỉ công khai PCB và tài nguyên KiCad cần thiết, không gồm dataset, AI, mô phỏng hoặc firmware. Chưa chạy lại DRC, chưa xác nhận hoạt động trên bo thật hoặc hiệu quả sử dụng hỗ trợ tiếp cận. Giấy phép riêng cho thiết kế PCB chưa được chọn.
