��Ŀ���ƣ�PKUMap������������Ա����һ����ͼ��������app
���ߣ�touma���ҵ�Ӣ������



�����ļ���PKUMap/app/src/main/AndroidManifest.xml
���������õ�API���������Ȩ�ޡ�APP��activity



���벿�֣�PKUMap/app/src/main/java����������ԼΪ2000+��
1 �������ṩ�Ŀ�Դdemo
1.1 com.baidu.location�����ٶȵ�ͼ�Ķ�λ����
1.2 com.baidu.mapapi.overlayutil�����ٶȵ�ͼ����ʾ�����ǡ�·�߹滮��
1.3 com.iflytek.speech�����ƴ�Ѷ���ṩ�������ϳɹ���
1.4 com.yuyh.library����GitHub��yuyh�ṩ���Զ������ݿؼ�

2 �Լ���д�Ĳ���
2.1 touma.pkumap��
2.1.1 IntroActivity�ࣺ����������activity
2.1.2 MainActivity�ࣺ��ӭ�����activity
2.1.3 PKUMapActivity�ࣺ��ͼ�������activity
2.1.4 RecognizeActivity�ࣺ����ʶ������activity
2.1.5 SearchActivity�ࣺ���������activity

2.2 touma.pkumap.util��
2.2.1 HttpClientUtil.java�����������࣬���ǵĹ���������org.apache.http������http�Ͻ�����ȫ���ӣ����ں�APP��������ͨ��
2.2.2 MyNavigation�ࣺ������ٶȷ������첽������������
2.2.3 MyRecognition�ࣺ������APP���������첽����ͼƬʶ������
2.2.4 MyPoiInfo�ࣺPoI��ָPlace of Interest���ٶȹٷ��������������ʾ������Ȥ��/���㡣����ඨ����һ�����������ȫ����Ϣ������APP���������첽�������Щ��Ϣ������

2.3 touma.pkumap.view��
2.3.1 PoiInfoView�ࣺһ���Զ���ĵ��������������ʾ����ļ�����Ϣ



��Դ���֣�PKUMap/app/src/main/res
1 �ļ���./drawable������У���ͼͼ���ļ���icon��ͷ��png�ļ���������ͼƬ�ļ���pkumap.jpeg������ɫ�����ļ���xml�ļ�����
2 �ļ���./layout
2.1 activity_intro.xml������������activity�Ĳ����ļ�
2.2 activity_main.xml����ӭ�����activity�Ĳ����ļ�
2.3 activity_pku_map.xml����ͼ�������activity�Ĳ����ļ�
2.4 activity_recognize.xml������ʶ������activity�Ĳ����ļ�
2.5 activity_search.xml�����������activity�Ĳ����ļ�
2.6 view_poi_info��PoiInfoView��������Ĳ����ļ�
2.7 view_poi_approach��������ĳ������ʱ����������������ʾ�ؼ�
2.8 view_poi_query��������/����ʶ�𷵻ؽ��ʱ����������������ʾ�ؼ�



�������岿�֣�PKUMap/app/src/main/values



������API��jar����PKUMap/app/src/main/jniLibs