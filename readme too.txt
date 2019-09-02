#!/bin/bash
apt install flatpak
flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
flatpak install flathub com.unity.UnityHub
flatpak run com.unity.UnityHub