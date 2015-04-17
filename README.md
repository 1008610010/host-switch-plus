# Host Switch Plus - Chrome Extension

Based on [Chrome Host Switch](https://github.com/shendongming/chrome-host-switch)

Change the hosts rules in Chrome. It's easy, and effect immediately.

I just want to make the web developers works happy if they often need to switch hosts between develop/test/production environment.

One more feature is that you can set a local proxy for some kind of domain, For example, if you use Fiddler AutoResponder, you can set the domain IP as 127.0.0.1:8888.

By the way, 
1. if you use windows system and just want to easy to manage you system hosts config, I recommend a windows tool called [SwitchHosts!](http://oldj.net/article/switchhosts/)
2. If you use Fiddler, it had a hosts tool under menu Tools > HOSTS, but I think it's difficult to manage the host rules.

Sorry for my Poor English, learn more from the screenshots please.

Any questions/issues let me know: https://github.com/Riant/host-switch-plus/issues

���� [Chrome Host Switch](https://github.com/shendongming/chrome-host-switch) �޸����ơ�������лԭ���߿�Դ����

> ����ip�л�����:
> 
> ���� ����PAC �Զ��л�һ��������IP���������޸� hosts, ����web������Ա�� ����/����/����/���� ���������л�

ͨ���� Chrome ��չ����ݷ�����л������� host �������

```
IP:�˿� ���� tag ��ע
127.0.0.1:8888 www.xyz.com prod Fiddler
127.0.0.1 *.xyz.com
192.168.1.2 www.xyz.com
```

#��Ե
�ڳ��򿪷������У����⿪�������ԡ��������������л���һ������ֱ���޸�ϵͳ�� hosts �ļ���

��ô���ļ������⣺

1. �༭�������鷳���Ƽ� [SwitchHosts!](http://oldj.net/article/switchhosts/)��

2. ��Ч�ӳ١��� Fiddler ��ͬѧ���������� Tools �µ� HOSTS ���ߣ�������������������ǻص��˵�һ�������ϡ�

���ˣ��ܷ���һ�����߹����㣬�ֿ�ݼ��أ����ҵ�һ�� Chrome ��չ [Chrome Host Switch](https://github.com/shendongming/chrome-host-switch)�������ƺ�����ˡ�

����Ϊ���� Fiddler���һ�װ�˲�� [Proxy SwitchySharp](https://chrome.google.com/webstore/detail/proxy-switchysharp/dpplabbmogkhghncfbfdeeokoefdjegm?utm_source=chrome-ntp-icon)

�� Chrome �Ĵ�����ֻ��ͬʱ��һ����Ч����ô��û��ʲô�취����һ���أ�

��л Chrome Host Switch ���� Github ��Դ�����ź������� Issues һֱû�л�Ӧ����������Ҳ�Ǻܾ�û�и����ˣ������Լ����ְɡ�

��ſ����´���ʵ�ֲ��֣������޸���һ�£�ͬʱ������ԭ����û����ɵı༭��������ӵȹ��ܣ�ͬʱ������һ��������Ӧ���IP ʱ��ֻ����һ����Ч�ļ�⣬���������ļ��ܴ��ô������ Bootstrap ���� Js �����

�������æ��û����ϸ�������ƣ��κ����ʣ����飬��ӭ[�ύ Issues](https://github.com/Riant/host-switch-plus/issues).

##ע��
1. �ð汾��ʱû��֧��ԭ�� Host Switch �ı�������
    192.168.1.110 web1
    #web1  www.wwbaidu.com




