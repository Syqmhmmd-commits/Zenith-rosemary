# Zenith Kernel - Rosemary

Release kernel untuk **Redmi Note 10S / POCO M5s (Rosemary)** berbasis **Vendor S**.

## 📱 Device Info

| Item | Detail |
|---|---|
| Device | Redmi Note 10S / POCO M5s |
| Codename | rosemary |
| Kernel | 4.14.332-Zenith |
| Android | Vendor S (Android 12+) |
| Arch | arm64 |

## ✨ Fitur

### Kernel KSU
- ✅ **KernelSU Next** (Manual Hook, tanpa KPROBES)
- ✅ Fix `selinux_hide.c` untuk kernel 4.14
- ✅ Nama kernel: `4.14.332-Zenith`

### Kernel Non-KSU
- ✅ Source kernel polosan (vendor S)
- ✅ Tanpa patch KSU
- ✅ Siap untuk build stock

**Keduanya:**
- ✅ Build dengan **Proton Clang 13**
- ✅ Support vendor S

## 🛠️ Cara Flash

1. **Backup** boot.img lama
2. Boot ke **Custom Recovery** (TWRP/OrangeFox)
3. **Pilih varian**:
   - Mau root? Flash `Zenith-Rosemary-ksun-*.zip`
   - Mau stock? Flash `Zenith-Rosemary-non-*.zip`
<<<<<<< HEAD
=======

## 💬 Diskusi & Support

- **XDA Thread:** [Zenith Kernel for Rosemary](https://xdaforums.com/t/kernel-4-14-zenith-kernel-for-rosemary-ksu-non-ksu.4804961/)

   ```bash
