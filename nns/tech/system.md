# NNSϵͳ����

�ο��ĵ�
>
>[NameHash�㷨���](namehash.md)
>
>[NNSЭ��淶](protocol.md)
>
>[����������Լ���](contract_nns.md)
>
>[�����ߺ�Լ���](contract_owner.md)
>
>[ע������Լ���](contract_register.md)
>
>[��������Լ���](contract_resolver.md)
>
# NNS ��ʲô
NNS��Neo������������һ������Neo�������ķֲ�ʽ����Դ�Ϳ���չ������ϵͳ��


NNS���Խ���������������Ŀ�ꡣ���������뵽����Neo�ĵ�ַ��Address�����������ܺ�Լ��ScriptHash����������������ϵͳʱԤ�����㹻����չ�ԣ�������NNS�������������֧�ָ���Ľ���Ŀ�����ࡣ
# NNS ϵͳ�Ĺ���
NNSϵͳ����������
һ�ǽ�beautiful.neo ������ɶ������ƽ���Ϊ����ʹ�õı�ʶ������Neo�ĵ�ַ�ȡ�
����Ϊ�����ṩ���������ݣ�����whois����Լ�ӿ�������

NNS �� DNS��Ŀ�����ƣ�����˵��ENS��Ŀ��һ��^_^�������������ܹ���ơ�ʹ�ú�DNSһ���õ�(.)�ָ��������ϵͳ����������߶���������������������ȫ�ķ���Ȩ����

.neo .gas �����ĸ�������һ����Ϊ��ע����Registry�������ܺ�Լ������һ��ע��������һ�������������趨ȡ����һ����������Ȩ�Ĺ����κ��˾������ն�Ӧ��ע�����趨�Ĺ���ȡ��һ������������Ȩ��

# NNSϵͳ�ܹ�
NNS���ĸ�ϵͳ���
1.  ����������Լ���������ǹ����������Ľű���
2.  �����ߣ������߿�����һ��address��Ҳ������һ�����ܺ�Լ��
3.  ע�����ר�Ÿ����һ�����������������������ߵ����ܺ�Լ��������Ҳ��ָ��һ����������ע�����
3.  ���������������һ����������������������

## ����������Լ
��������һ�������� ����.test ������Ϣ�Ĺ����ߡ�
���۶�������   aa.test ���� �������� bbb.aa.test,���ǵ������߶�������������֮�С�
���������ֵ����ʽ������������
1.  ������������(owner)
2.  ������ע����(register)
3.  �����Ľ�����(resolver)
4.  ������TTL(��������ʱ��)

### ������
�����������߿�����һ���˻���ַ����һ�����ܺ�Լ��
��ens�������ӵ�����������ܺ�Լ����ע������ʵ����ע����ֻ��owner��һ�����������ǽ������������ߺ�ע�����ֿ��ˣ����ϵͳ���ø���������

������������(owner)����
1.  ������������Ȩת�Ƶ���һ����ַ
2.  ����ע�������������ע����Ϊ������Ա�ֶ�������������
3.  ���Ľ�����

������������һ�����ܺ�Լ�������ṩ���ֶ���������Ȩģʽ
1.  ����˫�˹���������Ҫ����ǩ���ſ���ת���������߸���ע����
2.  ������˹�������������50%��ǩ���ſ���ת���������߸���ע����

�����������������һ���˻���ַ����ô�û����Ե���ע�����Ľӿڹ�������������
### ע����
��ens�������ӵ�����������ܺ�Լ����ע������ʵ����ע����ֻ��owner��һ��������
���ǽ������������ߺ�ע�����ֿ��ˣ����ϵͳ���ø����������󲿷��û�������ȥ���Լ��Ķ������������Դ󲿷��û���������ע���������ý��������ɣ�

ע����ר�Ÿ���һ�����������������·�������������ߡ�
ע����������������ű����в�����
����������ע�����Ƿ���Ȩ�޲�����������
ע��������������
1.  ��һ�����������������·�������������ߡ�
2.  ��ѯһ����������ӵ�����Ƿ�Ϸ�����Ϊ�����������������ˣ�Ȼ���������ת�ø��������������
����������������������£��������̻�ѯ��ע�����������¼������ǲ��Ƿ������ָ���������ߣ����û�У���˽�����Ч��

ע������һ�����ܺ�Լ�������в�ͬ�����ע������
1.  �ȵ��ȵ�ע��������ҿ���������������
2.  ����Ա�ֶ�����ע��������һ������Ա�����ý�������������Ȩ��δ���
3.  ����ע�������ȵȡ�



## ������
NNS����Ҫ�Ĺ��ܣ�������ɴ���������������ӳ�䡣
��������һ�����ܺ�Լ���������ʵ�ʽ����ַ���ɵ�ַ��ʵ�ʹ��̡�

ֻҪ��ѭNNS�������淶�����ܺ�Լ�Ϳ��Ա�����Ϊ��������NNS���ṩͨ�õĽ�������

���Ҫ�����µ�Э�����ͣ��ڶ�����NNS�淶û�е߸��Ըı������£������Բ���Ķ�NNSϵͳ��ֱ������ʵ�֡�

# �����������
## �����Ĵ洢
NNS�д洢������Ϊ32�ֽ�ɢ��ֵ������������ԭ�ĵ��ı������м������ԭ��
1.	��������ͳһ���������ⳤ�ȵ�������
2.	һ���̶ȱ�������������˽
3.	������ת��Ϊɢ�е��㷨��ΪNameHash�����ǽ����������ĵ������ж������н��͡�
NameHash�Ķ��巽ʽΪ�ݹ�ʽ

    ```
	����aaa.neo ��Ӧ��
	hashA  =  hash256(hash256(��.neo��) + ��aaa��)
	Ȼ�� bbb.aaa.neo��Ӧ��
	hashB  =  hash256(hashA+��bbb��)	
	��ô ccc.bbb.aaa.neo ��Ӧ��
	HashC  =  hash256(hashB+��ccc��)
    ```
�����Ķ��巽ʽ�����ǿ��Խ����в�ε�������һ����������������������ƽ���ı�����һ��Map<hash256, ������> �����ݽṹ�С�

������ע�����������������ķ���

����ݹ����NameHash�ķ�ʽ��������һ����������
Hash = NameHash(��xxx.xxx.xxx����);
NameHashʵ�ַ�������׫�ġ�

���е�ע���������뱻���浽������

## ��������
�û����ø������Ľ����������н������������ṩ�����Ϳ������ֽ�����ʽ���ɸ�����Ҫ���ã�Ҳ����ֱ�Ӳ�ѯ�����������е��á�

## ���ٽ�����ʽ
���ٷ�ʽ������ֱ�Ӳ�����������Ľ����������û�У���ѯ�������Ľ�������Ȼ����ý�����������

���ٷ�ʽ��������٣������ܴ���һ��©������Ϊ�������������˱��ˣ����������ڣ����Ƕ��������Ѿ�ת�õ������
��ʱ��Ȼ������������

## ����������ʽ
������ʽ�����������Ӹ�������ʼ�����������Ȩ��TTL����������Ͻ�ʧ�ܡ�

��������϶࣬��������������������
