# xyzzy

xyzzy ��[�T��N�펁](http://www.jsdlab.co.jp/~kamei/) ���J�������ACommon Lisp ���ۂ�����Ŋg���\��
Emacs ���ۂ��e�L�X�g�G�f�B�^�̂悤�Ȃ��̂ł��B
2ch �Ƃ� Twitter �Ƃ��ܖڕ��ׂ��ł�����A�e�L�X�g�t�@�C���̓ǂݏ������ł��܂��B

���݂͋T�䎁�ɕς��L�u�ɂ���ĊJ�����p�����Ă��܂��B


----

## xyzzy 0.2.2 �n��Ƃ�

xyzzy 0.2.2 �n��͈ȉ��̊ϓ_���d�������o�[�W�����ł��B

  * xyzzy 0.2.2.235 �Ƃ̌���݊���
    * xyzzy �͉ߋ��ɍ��ꂽ���Y�̂��������e����Ă��Ȃ����̂����\����܂����A
      �������C�������ɓ���ł��邱�Ƃ���Ώ����ł�
    * ���̂��߂ɂ͂��Ƃ��o�O�ł������Ȃ����Ƃ�����܂�
  * Common Lisp �Ƃ̌݊������d��
    * �������A0.2.2.235 �Ƃ̌݊������ۂ����ꍇ�̂�
    * CL �Ɠ��삪�Ⴄ�����ŉߋ��̎��Y�ɉe����^���Ȃ������Ȃ��̂͏C������
    * CL �Ɠ��삪�Ⴄ�����ŉߋ��̎��Y�ɉe����^������̂́A
      common-lisp �p�b�P�[�W�܂��� common-lisp-user �p�b�P�[�W�Œ�`����
  * ���萫
    * �\���e�X�g���Ă���l�X�ƃ����[�X����

�ȉ��̊ϓ_�ɂ��Ă͓��ɏd�����܂���B

  * �O���݊���
    * �V�K API �Ɉˑ������A�v���� 0.2.2.235 �œ����Ȃ��͓̂�����܂�
    * �O���݊������C�ɂ��Ă���ƑO�ɐi�߂Ȃ�
  * multiframe �ł� unicode �łƂ̌݊���
    * ����������L�h���o�[�W������ 0.2.2.235 �ƌ݊������Ȃ�����
    * multiframe �ł� unicode �ł̂����݊����ɉe����^���Ȃ��C���͎�荞��

���̔h���łƂ̈Ⴂ�͈ȉ��̂Ƃ���ł��B

  * multiframe �łƔ�ׂāA��� xyzzy �ŉ�ʂ������ς��J������o���܂���B
    ���̑��� 0.2.2.235 �ƌ݊���������܂��B
  * unicode �łƔ�ׂāA���j�R�[�h�ւ̑Ή������r���[�ł��B
    ���̑��� 0.2.2.235 �ƌ݊���������܂��B

�p��:

  * ����݊��� = 0.2.2.235 �ȑO�ɏ����ꂽ���̂� 0.2.2.236 �ȍ~�ł����삷�邱��
  * �O���݊��� = 0.2.2.236 �ȍ~�ɏ����ꂽ���̂� 0.2.2.235 �ł����삷�邱��


----

## �J��

https://github.com/xyzzy �͂��łɃA�J�E���g������Ă����̂� https://github.com/xyzzy-022
�Ƃ��� GitHub Organization �ōs���܂��B

�J���������l�� Organization �ɒǉ�����̂ŁA�Ƃ肠���� Pull Request �𑗂��Ă��������B

  * �u�����`���f���� [A successful Git branching model] �ɏ]���܂�
    * topic �u�����`�Adevelop �u�����`�Arelease �u�����`�Amaster �u�����`
    * topic �u�����`�ŊJ������ develop �u�����`�� `merge --no-ff`
    * Fast Forward �� merge ���Ɩ�肪���������� revert ����̂��ʓ|�Ȃ̂ŁA���Ȃ炸 `--no-ff` �Ń}�[�W�R�~�b�g�𐶐�����
    * master �u�����`�͏�Ƀ����[�X�\�ȏ�Ԃɒu��
  * �`�P�b�g�E�h���u��
    * �Ƃ肠�����C�Â������Ƃ� GitHub Issues �ɓo�^���Ă���
    * �����Ȃ� Pull Request �ł��悢
    * ���łɂ���`�P�b�g�����������Ȃ� Pull Request ���Ɍ��̃`�P�b�g�̔ԍ����L�ڂ���
  * �`�P�b�g�̎d��
    * �Ă��Ɓ[��
  * ChangeLog �͏����Ȃ�
    * merge ���ɃR���t���N�g���܂����Ă߂�ǂ�����
    * �`�P�b�g�ɏ����΂���
  * �R�~�b�g���O�̏�����
    * Git �� (���[���݂����Ȃ��) �ɏ]�������{��ŗǂ�
    * �G���R�[�f�B���O�� UTF-8 ��
  * �R�[�f�B���O���[��
    * ��{�I�ɂ͌��X�̋T�䂳��̃R�[�h�ɍ��킹�܂�
      * misc/mode-settings.l ��ǂݍ���ł����Ă�������
    * �������A�ȉ��̓_�͕ς��܂�
      * �w�b�_�t�@�C���̃v���g�^�C�v�錾�ň������͂����Ə���
      * C++ �X�^�C���̃L���X�g�𗘗p (static_cast, const_cast, reinterpret_cast, dynamic_cast)
        * <http://msdn.microsoft.com/ja-jp/library/cc440191(v=vs.71).aspx>
        * <http://msdn.microsoft.com/ja-jp/library/cc440192(v=vs.71).aspx>
      * XML �h�L�������g���L�q
        * <http://msdn.microsoft.com/ja-jp/library/ms177227.aspx>
  * push �܂��� Pull Request ����O�Ɉȉ����m�F
    * `build.bat` �� `build.bat Debug` ���x���Ȃ��Ńr���h�ł��邱��
    * `run-tests-all.bat` ���p�X���邱��
  * .gitconfig �Ɉȉ���ݒ肵�Ă���

    ```ini
    [i18n]
            commitencoding = utf-8
            logoutputencoding = utf-8
    [gui]
            encoding = utf-8
    ```

  [A successful Git branching model]: http://keijinsonyaban.blogspot.com/2010/10/successful-git-branching-model.html

----

## �����[�X

  * �����A���̓������[�X
  * �o�[�W�����ԍ��� 0.2.2.x �� x �����������[�X�̂��тɃC���N�������g
    * �C���̑召�ɂ�����炸��� 1 �Â��₵�Ă���
    * 0.2.2.65535 �܂Ŏg����


----

## �T�|�[�g OS

  * Windows XP SP3 �ȍ~���T�|�[�g


----

## �r���h���@

### ��

  * Visual C++ 2010 Express SP1
    * <http://www.microsoft.com/japan/msdn/vstudio/express/>
  * Windows SDK
    * <http://www.microsoft.com/download/en/details.aspx?id=8279>
  * msysGit
    * <http://code.google.com/p/msysgit/>
  * 7zip
    * <http://www.7-zip.org/>
    * �����[�X��Ǝ��̂�
    * 7za.exe ���p�X�̒ʂ����Ƃ���ɒu��

### �菇

 1. build.bat
    * �f�o�b�O�ł� build.bat Debug
 2. bytecompile.bat
 3. �ۂ��[�Ƒ҂�
 4. �ł�������
 5. run-tests.bat �Ń��j�b�g�e�X�g�����s

----

## ���C�Z���X

MIT ���C�Z���X�ł��B
�ڍׂ� LICENSE �t�@�C�����Q�Ƃ̂��ƁB
