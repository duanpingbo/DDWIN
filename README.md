# �ȿ����е�һ��DD Win�ű�

������ȫ�Զ�dd��װWindows

ͻ��û��VNC,û�о�Ԯģʽ,�ڴ��dd��С������.

ʹ��Debian Live CD�е�busybox���м�ý��,�������ӵĴ���,

ʹ�����������������Windows����ϵͳ��,

��ʹû��DHCP�ܹ���Windows��ȡ�������,

Ҳ����Windows����ϵͳ�ڿ����ĵ�һʱ���ܹ���ͨ����.


## 1.����:
```
#Debian/Ubuntu
## һ���Դ�
#RedHat/CentOS
yum install glibc-common
```

## 2.����:
��Ҫ����dd��.

��������Administrator�˻���¼(�����Զ���½)..

����Զ������(Ĭ��3389�˿�).

����UAC..

�ʵ��ĵ�������ǽ.(��ѡ)

��Ҫ��ص����⻯����.

VirtIO����(��������) XEN����(��������)

dd����ѹ���������ܳ���������һ��Ӳ�̵�����ݻ�.


## 3.ʹ�÷���:

``` 
wget --no-check-certificate -qO InstallNET.sh 'https://moeclub.org/attachment/LinuxShell/InstallNET.sh' && bash InstallNET.sh -dd '[Windows dd��ֱ����ַ]'
``` 

## �ȿ��ṩ��demo��(1.19G;�Ѽ���):
``` 
https://moeclub.org/get-win7embx86-auto
# �ȸ��ļ�ID: 1srhylymTjYS-Ky8uLw4R6LCWfAo1F3s7
# �ð�ֻ�����VirtIO����,�����Ͻ�����KVM,Hyper-V��������������.
# �������������⻯����������,���������������⻯����.
``` 
ʹ�õ���Windows Embedded Standard 7(Thin PC)��Ϊ�װ�,�ٷ�����.

�����������,����:��������������,Windows��Ƭ�鿴����.

��ο�: Thin PC (Win7 Embedded) ��װ���


## 4.ʹ��ʾ��:
```
#����Ļ�����ȫ�°�װ,�������VNC,���Կ���ȫ������.
#��dd�Ĺ�����,�Ῠ�ڷ����Ľ�����,�����߽�����.��ɺ󽫻��Զ�����.
 
wget --no-check-certificate -qO InstallNET.sh 'https://moeclub.org/attachment/LinuxShell/InstallNET.sh' && bash InstallNET.sh -dd 'https://moeclub.org/get-win7embx86-auto'
```

## 5.ʹ��ʾ��(ָ���������):
```
# ��X.X.X.X�滻Ϊ�Լ����������.
# --ip-addr :IP Address/IP��ַ
# --ip-mask :Netmask   /��������
# --ip-gate :Gateway   /����
# wget --no-check-certificate -qO InstallNET.sh 'https://moeclub.org/attachment/LinuxShell/InstallNET.sh' && bash InstallNET.sh --ip-addr X.X.X.X --ip-mask X.X.X.X --ip-gate X.X.X.X -dd 'https://moeclub.org/get-win7embx86-auto'
```


## 6.ע������:

1)Զ�̵�½�˺�Ϊ: ```Administrator```

2)Զ�̵�½����Ϊ: ```Vicer```

3)���޸���������,�ɷ���ʹ��.(�����Լ�����.)

4)ʹ�õĹ�������,���賤��/����ʹ�ô˰������б���.

5)������Υ����TOS,�ȿ������κ�����.


## 7.�����õ�������:
```
::�Թ���Ա�������CMD::
 
::�����û�������
net user [�û���] [����]
::���� Administrator �˻�
net user Administrator /active:yes
::���� Administrator �˻�����
net user Administrator [������]
::����û�
net user [�û���] [����] /add
::���û������ Administrator ��
net localgroup Administrators [�û���] /add
::ɾ���û�
net user [�û���] /del
```

## 8.��ܰ��ʾ:
�ڴ��̹�����,�����C����,�Ҽ�ѡ����չ��,����ֱ�ӡ����ӡ�C�̵Ŀռ�.

���������ο�: https://moeclub.org/kms

## 9.�ȿ��ṩ�Ŀ��ð�:

�뱾����iso����װ����һ��,�������VNC,�ɿ���ȫ������.

��Ϊȫ�°�װ!!! ȫ�°�װ!!! ȫ�°�װ!!! ���Ի�ȴ���һ��.

Windows Embedded 8.1 Industry Pro x64 (2.87G;KVM;XEN;Hyper-V;δ����)
```
ֱ��:
https://moeclub.org/get-win8embx64-auto
�ȸ������ļ�ID:
1cqVl2wSGx92UTdhOxU9pW3wJgmvZMT_J
```

ת�����ȿ�https://moeclub.org/2017/11/19/483/