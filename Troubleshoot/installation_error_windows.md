1) Open cmd as Admin mode Then type below commands

2) systeminfo.exe

3) DISM /Online /Disable-Feature:Microsoft-Hyper-V

4) bcdedit /set hypervisorlaunchtype off

5) shutdown /r /t 0

6) Again start minikube with 'minikube start'
