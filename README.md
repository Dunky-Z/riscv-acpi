# riscv-acpi

= RISC-V ACPI Platform Specification

This document specifies the mandatory ACPI requirement for the RISC-V server
class platforms.

Discussion of ACPI related changes occurs on the
https://lists.riscv.org/g/tech-unixplatformspec[RISC-V Unix Platform Mailing
list]. It is publicly readable but posting requires being a member of the
RISC-V Foundation. Any new ACPI requirement needs to be discussed and approved
there before being merged.

= Licensing

The files in this repository are licensed under the Creative Commons
Attribution 4.0 International License (CC-BY 4.0).  The full license
text is available at https://creativecommons.org/licenses/by/4.0/.

= Building Documents

The final specification in form of PDF and HTML can be generated using
`make` command. The `makefile` internally uses asciidoctor so the packages
required by the `makefile` need to be installed on the build system using
`make install-debs` or `make install-rpms`.

Detailed Engineering Change Request (ECR) review process and individual ECRs are 
documented [here](https://github.com/riscv/riscv-acpi/wiki/ACPI-ASWG-ECR-Process) 
