# Welcome to the NGPL wiki!  
  
I have to say sorry about this project is written in Japanese programing language, "Nadesiko(�Ȃł���)",  
so you may be cannot hack this project.  
But... if you are highly motivated, we are welcome you !  
  
**N**adesiko **G**ame **P**rograming **L**ibrary  
======================  
�Ȃł������Q�[���v���O���~���O���C�u����  

* �`���[�g���A����  
* �A���S���Y���̃e�X�g��  
* ���I�Ȑ}����A�j���[�V������  
  
   �ō��̃p�t�H�[�}���X��񋟂��܂��B  
 
 
�g����
------
 
### NGPL�ɂ��R�[�f�B���O
  
NGPL�͂ƂĂ��V���v���ɐ݌v����Ă��܂��B  
���݂͂قƂ�ǂ̋@�\���J�����ł����A���[�U�[�ɂƂ��Ē����I�ŕ�����₷���C���^�[�t�F�C�X��񋟂��܂��B  
  
�ȉ��͂��̃R�[�f�B���O�̗�ł��B  
  
    GPLInit()                              # NGPL�̏�����
    GPLBufferScreenParam(0,0,400,200,0)    # x,y,w,h,�F�ŁA�o�b�t�@�X�N���[��������������
    BufferScreen��InitUserColor($ff0000)    # ���[�U�[�̔C�ӂ̃J���[�ō�����ʃN���A�����邽�߂̏����� (�C���[�W�P���̃������������)�i�I�v�V�����j
	
    A��Graphic_g�Ƃ��č쐬                     # ���[�U�[���g���ۂ�Graphic_g���p������
    B��Graphic_g�Ƃ��č쐬
    A��Load(`Magicsquare_b.bmp`)            # �������ɉ摜�����[�h����B(bmp�̂�)
    B��Load(A��Same())                       # A�Ɠ����摜���g���ă��[�h����B
    B��x = 100
    
    # ���[�v�ł͂�������J�n
    # �o�b�t�@�[��ʂ̃N���A
    BufferScreen��UserClear()
	
    # �O���t�B�b�N�I�u�W�F�N�g�̕`��
    A��Draw()
    B��Draw()
	
    # �o�b�t�@������ʂɃt���b�v���āA�o�b�t�@�͏�������B�iDONTCLEAR==1�Ȃ�Ώ������Ȃ��j
    BufferScreen��Flip()
	
    # �O���t�B�b�N�I�u�W�F�N�g�̔j��
    A��Delete()
    B��Delete()

�����GPL�̃��C���t�@���N�V�������L�q����Ă���\�[�X�R�[�h�ɕt������ق�̃T���v���ł��B  
�Ȃł������̂��̂��ƂĂ��V���v���ɐ݌v����Ă��܂����A�����Q�[������낤�Ƃ���Ύv���̊O�K�v�Ȃ��̂��������ƂɋC�t���ł��傤�B  
  
���̒��ł͔ėp�����������Ȃ�����A����C�Ȃ��֗��ȋ@�\�𑽐����ڂ��Ă��܂��B  
NGPL�ł͕W���Ƃ��Ĉȉ��̋@�\��񋟂��܂��B  

## �W���@�\ ##

    1. �_�u���o�b�t�@�����O  

    2. �C���[�W�̍����`��

    3. �C���[�W�̉�]�E�g��`��

    4. �C���[�W�̐F�����`��

    5. �t���[���Ԋu����(FPS�̌Œ�)

    6. �I�u�W�F�N�g���m�̓����蔻��

    7. �Ȑ��n�֐�


  
�֘A���
--------
  
* [GAMERSLIB](https://sites.google.com/site/tatumakiprojectn1/sakuhin/tatumakigen/game-s-library "GAMERSLIB")  
GAMERSLIB�͂��̃v���W�F�N�g�̑O�g�ƂȂ郉�C�u�����ł��B  
�����̃��C�u���������g���₷�����A�Q�[���p�r�ɓ������������̂�NGPL�ƂȂ�܂��B  
  
