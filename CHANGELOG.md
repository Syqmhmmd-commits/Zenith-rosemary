# Changelog

## v1.0 — 14 Oktober 2026

### Added
- Rilis pertama Zenith Kernel untuk Rosemary
- Kernel 4.14.332-Zenith
- Varian KSU: KernelSU Next dengan Manual Hook
- Varian Non-KSU: kernel polosan

### Fixed
- Fix `selinux_hide.c` untuk kernel 4.14 (ubah batas versi dari 4.17 ke 4.14)
- Hilangkan duplikasi "Zenith" di nama kernel

### Technical
- Build dengan Proton Clang 13
- Manual hook di 5 file: `fs/exec.c`, `fs/open.c`, `fs/read_write.c`, `fs/stat.c`, `kernel/reboot.c`
- Tanpa KPROBES (karena bug di kernel 4.14 MTK)
