3.1. ��������Ŀ
3.1.1. �°汾�⼴������Ŀ
��GitHub��һ����Ŀ��ӦΨһ��Git�汾�⣬����һ���µİ汾����Ǵ���һ���µ���Ŀ�������Ǳ�壨Dashboard��ҳ�棬��ͼ3-1�����Կ�����ע�İ汾�����Ѿ���һ�������Լ��İ汾��Ϊ�㡣����ʾΪ��İ汾���б��������һ����ť��New Repository��������ð�ť��ʼ�����°汾�⡣
../images/new-repo-btn.png
ͼ3-1���汾���б����
�½��汾��Ľ�����ͼ3-2��ʾ��
../images/new-project.png
ͼ3-2����������Ŀ
����Ϊ�½����İ汾������Ϊ��helloworld������Ӧ����Ŀ����Ϊ��helloworld����������Ϻ������Ŀҳ����ʾ�汾����δ��ʼ������������γ�ʼ���汾��İ�������ͼ3-3��ʾ��
../images/project-uninitial.png
ͼ3-3����Ŀ��δ��ʼ��
��ͼ3-3�п��Կ�������Э��������һ��֧�ֶ�д��SSHЭ�飬���ʵ�ַΪ��git@github.com:gotgithub/helloworld.git��ע���κ�GitHub�û�����ʹ�ø�URL���ʴ˹����汾�⣬��ֻ�а汾�⽨����gotgithub���ж�дȨ�ޣ�������ֻ��ֻ��Ȩ�ޡ��ڳ�ʼ���汾��֮ǰ�������ȷ���Ƿ�������ȷ�Ĺ�Կ������֤�����£�
$ ssh -T git@github.com
Hi gotgithub! You've successfully authenticated, but GitHub does not provide shell access.
3.1.2. �汾���ʼ��
����Ǵ�ͷ�����汾�⣬���Բ����ȿ�¡�������ύ���ݣ������ͨ���������GitHub�汾��ĳ�ʼ�����������£�
��¡�汾�⡣
��¡���̻���ʾ���棬�������������Ժ��ԣ���ΪGitHub�����İ汾�Ȿ������һ���հ׵İ汾�⡣
$ git clone git@github.com:gotgithub/helloworld.git
Cloning into 'helloworld'...
warning: You appear to have cloned an empty repository.
�����ļ�README.md[1]��
������һ��ʾ�����֣���������ֱ���Ϊ�ļ�README.md�����ļ������ݽ���ֱ����ʾ����Ŀ��ҳ�У���ʾЧ���μ������ͼ3-5����
# �ҵĵ�һ��GitHub��Ŀ

������Ŀ [helloworld](https://github.com/gotgithub/helloworld) ��
��ӭ���ʡ�

�����Ŀ�İ汾���� **Git��ʽ** ���� Windows��Linux��Mac OS X
ƽ̨���пͻ��˹��߿��Է��ʡ���Ȼ�汾��ֻ�ṩGitһ�ָ�ʽ��
�����㻹�ǿ������������������߷��ʣ��� ``svn`` �� ``hg`` ��

## �汾���ַ

֧�����ַ���Э�飺

* HTTPЭ��: `https://github.com/gotgithub/helloworld.git` ��
* GitЭ��: `git://github.com/gotgithub/helloworld.git` ��
* SSHЭ��: `ssh://git@github.com/gotgithub/helloworld.git` ��

## ��¡�汾��

����ʾ����

    $ git clone git://github.com/gotgithub/helloworld.git
����������ֲ���Markdown��ʽ����Ҳ����ʹ������֧�ֵĸ�ʽ��ֻҪȷ��README�ļ�ʹ����ȷ����չ�������鸽¼���ֽ�����Markdown������GitHub֧�ֵı�����ԡ�����Markdown��Ŀǰ����ֻ��֪����һ������ʶ������Ĵ��ı���ʽ�����Է����ת��ΪHTML��Markdown�﷨�ǳ���������д�ʼ������ı���ʱ�ÿ������ָ����䡢���Ǻſ����б���������ʾ�������ݵȵȡ�
���README.md�ļ����ύ��
$ git add README.md
$ git commit -m "README for this project."
��GitHub���ͣ���ɰ汾���ʼ����
$ git push origin master
Ȼ��鿴GitHub���½���Ŀ����ҳ����Ŀ��ҳ���ϰ벿�ֿɼ��汾�������һ���µ��ύ���Լ��汾��Ŀ¼���а������ļ�����ͼ3-4��ʾ��
../images/project-pushed-head.png
ͼ3-4��������ͺ����Ŀ��ҳ�ϰ벿��
����Ŀ��ҳ���°벿�֣��ῴ��README.md�ļ���ת��ΪHTML��ʾ����ͼ3-5��ʾ��
../images/project-pushed-tail.png
ͼ3-5��������ͺ����Ŀ��ҳ�°벿��
3.1.3. �����а汾�ⴴ��
�����GitHub��Ŀ��ʼ��֮ǰ�������Ѿ������ڱ��ذ汾���У���Ȼ�����������ȿ�¡�����ύ�������͵ķ����Ͳ������ˡ�Ӧ�ò�������ķ�����
Ϊ�����µİ汾���ʼ���������ȰѸո��½��Ĳ�����Ŀ��helloworld��ɾ����ͬʱҲ�����ع������п�¡�ġ�helloworld��ɾ�������棺ɾ����Ŀ�Ĳ����ǳ�Σ�գ����ɻָ������á�
�����Ŀ��ҳ����Ŀ�����Աߵġ�Admin����ť������Ŀ����ҳ���ٵ��ҳ�����·���ɾ���汾��ť����ͼ3-6��ʾ��
../images/project-delete.png
ͼ3-6��ɾ����Ŀ
Ȼ�����ؽ��汾�⡰helloworld�����籾��һ��ʼͼ3-2��ʾ��
������ʹ������Ĳ�����ɡ�helloworld���汾��ĳ�ʼ����
���ؽ���һ��Git�汾�⡣
$ mkdir helloworld
$ cd helloworld
$ git init
Ȼ���ڰ汾�������ʾ���ļ�����README.md�ļ�������ͬǰ��
$ git add README.md
$ git commit -m "README for this project."
Ϊ�汾�������Ϊorigin��Զ�̰汾�⡣
$ git remote add origin git@github.com:gotgithub/helloworld.git
ִ������������GitHub�汾��ĳ�ʼ����ע���������е�-u�����������ͳɹ����Զ��������ط�֧��Զ�̰汾���֧��׷�١�
$ git push -u origin master
[1]	����չ��.md��.mkd��.mkdn��.mdown��.markdown��Ϊ��β���ļ�������Markdown��������﷨���н�������ʾ��
