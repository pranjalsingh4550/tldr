# guestfish

> Interactive CLI shell to read and modify VM images
> Do NOT use with live VMs - may corrupt the image

- Launch the shell:
`guestfish`

- Launch the shell but read protected images (QEMU images are in /var by default):
`sudo guestfish`

- Launch shell and [a]dd a disk image (behaves as if in working directory `/`)
`guestfish --add {{path/to/image}} --inspect

- Launch a shell with an image, but 
