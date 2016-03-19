# gpu-switch

Простой скрипт, предназначенный для смены видеодрайвера в системе Gentoo. 

Установка: layman -a qwin-overlay && emerge gpu-switch
Использование: gpu-switch nouveau / gpu-switch nvidia

При использовании xorg.conf для каждого драйвера:
/etc/X11/xorg.nvidia и /etc/X11/xorg.nouveau
Скрипт сам все найдёт и установит.
