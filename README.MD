  This recurse is download vbox
   'https://app.vagrantup.com/xoan/boxes/proxmox-ve_6.2/versions/1.0/providers/virtualbox.box'
  EOF
git init
git lfs track "*.box"
git add .
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:linux8a/VBOX_PROXMOX.git
git push -u origin main
