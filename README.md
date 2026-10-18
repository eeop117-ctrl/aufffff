# Сборка QEMU-iOS (iPod touch 2G) для Windows

1. Создай новый репозиторий на GitHub и залей туда всё из этой папки
   (важно, чтобы осталась папка .github/workflows).
2. Вкладка Actions -> "Build QEMU-iOS (iPod touch 2G) for Windows" -> Run workflow.
3. Когда сборка закончится, скачай артефакт qemu-ios-windows.
   - qemu/ : новый qemu-system-arm.exe и DLL. Положи поверх своей папки qemu\ (run.bat не меняй).
   - src/  : исходники устройств iPod (GPIO и др.) - пришли их Claude, чтобы написать патч для кнопки Home.
