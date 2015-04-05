INFO
====

Important info about building
====
DO NOT HESITATE TO CONTACT ME at http://forum.xda-developers.com/member.php?u=4764337

1. sync cm source  --> cm10x86 branch is more complete so sync cm10.1 using command:
- repo init -u git://github.com/CyanogenMod/android.git -b cm-10.1
- repo sync -f

2. git clone repositories from https://github.com/lenovo-k900/

3. . build/envsetup.sh

4. lunch (choose redhookbay)

5. make -j4 recoveryimage (to build recovery)

6. make -j4 otapackage (to build full ROM)
