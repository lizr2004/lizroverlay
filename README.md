## lizroverlay

Initramfs hook to mount overlayfs as rootfs.

| key | value |
| :-: | :-: |
| lizroverlay_upper | upper device |
| lizroverlay_upper_options | upper device mount options |
| lizroverlay_lower | lower device |
| lizroverlay_lower_options | lower device mount options |
| lizroverlay_tmpsize | use tmpfs as upperdir (without lizroverlay_upper) <br> 
    and declare the tmpfs size (default 256M) |

