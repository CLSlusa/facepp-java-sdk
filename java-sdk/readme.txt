SDKʹ�õ�һЩ˵����
Some instructions for using SDK,

���SDK���������������JAVA��API"HttpsURLConnection"д�ģ��Լ���װ��һЩ������������ǿ�ҽ���ʹ�õ�����������������ǵ�API
The network request in this SDK is written with JAVA API "HttpsURLConnection", some of its own network request package, it is recommended to use the third party framework to call our API


SDK��ļ�����
Several classes in SDK

Response ����һ����������Ľ���࣬��������Ľ����װ�����棬�������ص�״̬��ͷ��ص���Ϣ
Response: This is a result of a class of network requests, the results of the network package is included in the request, including the return of the state code stuta and return information content


CommonOperate ��װ��detect��compare��search�������ӿ�
CommonOperate: encapsulates the detect, compare, search these three interfaces


FaceSetOperate FaceSet��صĲ���
FaceSetOperate:FaceSet related operations


FaceOperate Face��صĲ���
FaceOperate:Face related operations

CardOperate ��װ��֤��ʶ��Ľӿڣ�ʹ�ù��ʰ�����������
CardOperate: interface for document identification��please ignore if you are use international version

ImageOperate ͼƬʶ��ӿڵķ�װ��ʹ�ù��ʰ�����������
ImageOperate: image recognition interface package��please ignore if you are use international version

BodyOperate ��װ��������������ͼ�Ĺ���
BodyOperate:HumanBody Detect and HumanBody Segment

HttpRequest �������װ����������
HttpRequest: This is a network request

Key �����涨����һЩ�ֶ�
Key: here are some fields defined

����Ĳ���˵�������������뿴ÿ��������ע��
Specific parameters and methods to see the function of each method notes