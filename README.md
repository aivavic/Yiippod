- Yiippod 1.0
_______________________________________________________________________________________

Flash and HTML5 video player without any logos or copyright on screen. Based on free
version of Uppod player(http://uppod.ru/). Support: FLV, MP4, AVI, MOV, RTMP, HTTP
//���� � ����5 ����� ����� ��� �����-���� ��������� � ���������� �� ������. ������� ��
���������� ������ Uppod ������ (http://uppod.ru/). ������������: FLV, MP4, AVI, MOV, RTMP, HTTP
_______________________________________________________________________________________

@author Alexander Shapovalov <mail@shapovalov.org>
//����� ��������� ��������� <mail@shapovalov.org>

Usage:
//�������������:

Download and extract in: yii_web_root/protected/extensions
//�������� � ���������� �: yii_��������_����������/protected/extensions

Add this code in your view:
//�������� ������ ��� � ������ �������������:

<?php  
 
	$this->widget('ext.Yiippod.Yiippod', array(
	'video'=>"http://www.youtube.com/watch?v=qD2olIdUGd8",
	'id' => 'yippodplayer',
	'width'=>640,
	'height'=>480,
	'bgcolor'=>'#000'
	));

?>

Where: 

'video' => address to media file or video stream,
'id' => player id,
'width' => player width,
'height' => player height,
'bgcolor' => player background color before player loading

//
���: 

'video' => ����� �� ����� ����� ���� ������ �����,
'id' => ������������� ������,
'width' => ������ ������,
'height' => ������ ������,
'bgcolor' => ������ ��� ������ ����� ��� ������ ���������
