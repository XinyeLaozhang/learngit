Git is distributed version control system.
Git is free software distributed under the GPI.
Git is a multabe index called stage.
Git tracks changes.



�ı乤��ȥ����
add, �������������ύ���ݴ���
git add <files>...
checkout, ���ݴ������ݸ��ǹ���ȥ������
git checkout <files>...



�ı��ݴ�������
���Ѿ��ύ���ݴ�������û���ύ���汾������ݳ���
git restore --staged <files>...
git reset HEAD <files>...
Ҳ���Խ����ڹ��������������ύ���ݴ���������ԭ���ģ�Ҳ������commit ֮ǰ��add һ��
git add <files>...


�汾����
git reset --hard HEAD^   (���� HEAD~n)
git reset --hard commitID


git status ���ݽ���
$ git status
On branch master
Changes to be committed:	////�Ѿ��ύ���ݴ����ˣ����ǻ�û���ύ���汾��
  (use "git restore --staged <file>..." to unstage)
        modified:   readme.txt

Changes not staged for commit:	////���������ݱ仯�ˣ����ǻ�û���ύ���ݴ���
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   readme.txt

