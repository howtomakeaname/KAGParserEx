Title: KAGParserEx �v���O�C��
Author: miahmie

������͉����H

KAGParser��u�������Ċg������v���O�C���ł��B
���肵����{�̑���contrib����\��ł����C
�󋵎���ł͂��̂܂܂ōs����������܂���B

���݂̂Ƃ���C�g�������͉̂��L�Q�_�݂̂ł��B
�Ȃ��C�d�l�͗\�������ύX�����ꍇ������܂��B


�E�^�O�̕����s�L�q���\�ɂȂ� multiLineTagEnabled �v���p�e�B�̒ǉ�

�@�s���� "\" ���L�q���C���̍s�̐擪�� ";" �����邱�ƂŁC
�@�����s�ɂ킽��^�O���L�q�ł��܂��B
�@���s���� "\" �݂̂Ŏ��̍s���� ";" ���Ȃ��ƃG���[�ɂȂ�܂��B

	@tag hoge=123 fuga=test \
	;    someoption=true \
	;    andmore=false

�@�s���� ";" ������̂́C���d�l�̃p�[�T�[�ɒʂ��Ă� ch �^�O�Ƃ���
�@�F������Ȃ��悤�ɃR�����g�Ƃ��閳������ adhoc �d�l�ł��B

�@"\" �̑O�ɂ͕K���P�ȏ�̃X�y�[�X���󂯂Ă��������B
�@�󂯂Ȃ��ƑO�̗v�f�Ƃ������ĔF������Ă��܂��܂��B
�@�܂��C�^�O���͕K���P�s�ڂɋL�q���܂��B

	; �_���ȗ�F
	@tag hoge=123\			�� hoge="123\"�ƔF��
	@tag hoge\			�� hoge\=true�ƔF��
	@ \				�� \ �Ƃ����^�O���ŔF��

�@���d�l�ł́C[�`]�\�L�ŕ����s�̃^�O���L�q����ꍇ�C���̃^�O������ȍ~��
�@����Ƀ^�O�𑱂��Ă����������悤�ɂȂ��Ă��܂��B
�@�i���s�^�O�������ő}������܂���j

	[tag hoge=123 fuga=test \
	;    someoption=true \
	;    andmore=false][���̃^�O�͖��������]

�EgetNextTag() �̋A��l���� "taglist" �����o��ǉ�

�@�ݒ肳��Ă���l�̓^�O�����L�ڏ��i�[���ꂽ�z��ł��B
�@�L�ڂ��ꂽ���ɃR�}���h�����������ꍇ�ɗL�p�ł��B

���\�[�X�ɂ���

KAGParser�̃\�[�X�����̂܂ܗ��p���������đg�ݍ���ł��܂��B
�\�[�X��svn copy���Ă���̂ŁC���O����{�̑�����̕ύX�_��ǂ����Ƃ��ł��܂��B

	KAGParser.cpp   <- src/core/utils/KAGParser.cpp
	KAGParser.h     <- src/core/utils/KAGParser.h
	tjsHashSearch.h <- src/core/tjs/tjsHashSearch.h


���g����

KAGParserEx.dll �������N����ƁCKAGParser�N���X���u�������܂��B
�A�������N����ƁC���ɖ߂�܂��B


�����C�Z���X

���̃v���O�C���̃��C�Z���X�͋g���g���{�̂ɏ������Ă��������B

