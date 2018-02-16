# Kernel Boot Process

This chapter describes the linux kernel boot process. Here you will see a
series of posts which describes the full cycle of the kernel loading process:

���̏͂ł̓J�[�l���u�[�`�v���Z�X�ɂ��ċL�ڂ���B
�����ŃJ�[�l�����[�f�B���O�v���Z�X�̃t���T�C�N���ɂ��Ă̈�A�̓��e�������B

* [From the bootloader to kernel](linux-bootstrap-1.md) - describes all stages from turning on the computer to running the first instruction of the kernel.

* [�u�[�g���[�_�[����J�[�l��](linux-bootstrap-1.md) - �R���s���[�^�[�̓d���I������J�[�l���̍ŏ��̖��߂����s�����܂ł̑S�ẴX�e�[�W�ɂ��Ă̐���

* [First steps in the kernel setup code](linux-bootstrap-2.md) - describes first steps in the kernel setup code. You will see heap initialization, query of different parameters like EDD, IST and etc...

* [�J�[�l���̃Z�b�g�A�b�v�R�[�h���̍ŏ��̃X�e�b�v](linux-bootstrap-2.md) - �J�[�l���̃Z�b�g�A�b�v�R�[�h���̍ŏ��̃X�e�b�v�ɂ��Ă̐����B�q�[�v�̈�̏������AEDD�AIST�Ȃǂ̂悤�ȈقȂ�p�����[�^�̖₢���킹

* [Video mode initialization and transition to protected mode](linux-bootstrap-3.md) - describes video mode initialization in the kernel setup code and transition to protected mode.

* [�r�f�I���[�h�̏������ƃv���e�N�g���[�h�ւ̈ڍs](linux-bootstrap-3.md) - �J�[�l���̃Z�b�g�A�b�v�R�[�h���ł̃r�f�I���[�h�̏������ƃv���e�N�g���[�h�ւ̈ڍs�ɂ��Ă̐����B

* [Transition to 64-bit mode](linux-bootstrap-4.md) - describes preparation for transition into 64-bit mode and details of transition.

* [64�r�b�g���[�h�ւ̈ڍs](linux-bootstrap-4.md) - 64�r�b�g���[�h�ւ̈ڍs�̏����ƈڍs�̏ڍׂɂ��Ă̐���

* [Kernel Decompression](linux-bootstrap-5.md) - describes preparation before kernel decompression and details of direct decompression.

* [���k���ꂽ�J�[�l���̓W�J](linux-bootstrap-5.md) - ���k���ꂽ�J�[�l���̓W�J�̏����ƃ_�C���N�g�W�J�̏ڍׂɂ��Ă̐���

* [Kernel random address randomization](linux-bootstrap-6.md) - describes randomization of the Linux kernel load address.

* [�J�[�l���̃A�h���X�̃����_����](linux-bootstrap-6.md) - Linux�J�[�l���̓ǂݍ��݃A�h���X�̃����_�����ɂ��Ă̐���
