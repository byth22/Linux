<b>Error:</b>

  ERROR MOUNTING /DEV/SDB1 AT /MEDIA/Byth22/BACKUP 1TB: COMMAND-LINE `MOUNT -T

<b>Error correction:</b>

  <pre>sudo apt-get install ntfs-3g</pre>
  <pre>sudo ntfsfix /dev/sdb1</pre>
