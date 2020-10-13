Install:
```bash
git clone https://github.com/zsa/qmk_firmware zsa_qmk
cd zsa_qmk
./util/qmk_install.sh
git submodule init
git submodule update
```

Make symbolic link:
```bash
ln -s /home/optozorax/my/moonlander ~/zsa_qmk/keyboards/moonlander/keymaps/optozorax
```

Flash:
```bash
make moonlander:optozorax:flash
```

Screenshot in kle.klava.org for firefox:
```
:screenshot layout/1 --selector '#keyboard-bg' --dpr 3
```

![](layout.png)