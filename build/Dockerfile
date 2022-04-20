FROM menci/archlinuxarm:base-devel

RUN pacman -Sy --noconfirm && pacman -S --noconfirm git

RUN useradd -m build

COPY all /etc/sudoers.d
