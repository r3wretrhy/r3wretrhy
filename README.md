# Zhaoqi Xu

I fix bugs in other people's open-source projects: firmware and RTOS code, build and packaging tools, and language runtimes.

**Highlights**

- Reported **CVE-2026-44726** to Deno ([GHSA-chqv-56wv-7564](https://github.com/denoland/deno/security/advisories/GHSA-chqv-56wv-7564)) and wrote the merged fix, [deno#32838](https://github.com/denoland/deno/pull/32838).
- **87 merged pull requests across 61 upstream projects**, including Deno, Apache NuttX, Apache Airflow, Zephyr, ESPHome, ninja, Meson, SCons, pip tooling, and Gitea.
- Most of these come with a regression test and go through the project's own review.

**Selected merged contributions**

| Project | What | PR |
|---|---|---|
| Deno | Keep the TLS upgrade state when a connection retries (security fix) | [#32838](https://github.com/denoland/deno/pull/32838) |
| riscv-isa-sim (Spike) | mstateen0 P1P13/ENVCFG bits read as zero when their CSRs don't exist | [#2467](https://github.com/riscv-software-src/riscv-isa-sim/pull/2467) |
| rp-hal | Fix overflow in the RP2040 UART fractional baud-rate divisor | [#1012](https://github.com/rp-rs/rp-hal/pull/1012) |
| Apache NuttX | ESP32-S3 SPI: make the CS/MOSI/MISO pin fields signed | [#20541](https://github.com/apache/nuttx/pull/20541) |
| ESPHome | Fix shifted fan speeds in the Mitsubishi MSC heat-pump IR protocol | [#20460](https://github.com/esphome/esphome/pull/20460) |
| Nuitka | `getattr()` default applies only to `AttributeError`, matching CPython | [#4078](https://github.com/Nuitka/Nuitka/pull/4078) |
| Apache Airflow | Beam async hook no longer launches pipelines through a shell | [#72510](https://github.com/apache/airflow/pull/72510) |
| ninja | `ninja_syntax`: escape paths in `Writer.default` | [#2837](https://github.com/ninja-build/ninja/pull/2837) |

**Areas:** embedded and RTOS (NuttX, Zephyr, ESPHome, embedded Rust), RISC-V, build systems and Python packaging (ninja, Meson, SCons, pip/virtualenv/pdm, PyInstaller), runtimes and security (Deno, Nuitka).

I use AI tools in my workflow, and I review and test everything I submit.

Contact: lzy00419@outlook.com
