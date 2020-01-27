<b>Error:</b>

  ERROR MOUNTING /DEV/SDB1 AT /MEDIA/Byth22/BACKUP 1TB: COMMAND-LINE `MOUNT -T

<b>Error correction:</b>

  sudo apt-get install ntfs-3g
  sudo ntfsfix /dev/sdb1
