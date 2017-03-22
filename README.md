# simple-news-aggregator

������������, ���������� ������:
http://jquiz.azurewebsites.net/newsaggregator/ <br>
(������� ������������, ������� ����� �������� �� ��������� ���������� :)

## �������:
����� �������� ��������� ��������.
������������ ������ �� ���� ����� ���������� ����� ��� ��� RSS-����� � ������� �������� (������ ������� � �� ���������� ������������).
1. ��������� � ���. ��������� �� ����� ������������.
2. ������� � ����� �����, �� �������� ������ ������ ������, ��� ������� ��� ��� ���� ����. ������ ��� ����� ���� � �� rss.

���� ������ ���������� �������� ������������� ����������� ��������� � ����� �����.<br>
� ������������ ���� ����������� ������������� ������ �������� �� ���� � ������ �� �� ��������� � ��������� �������.<br>
� �������� ������� ��������� ���������� ��� ����� ��������� ����� �� �����.<br>
��������� � �������� ��� ����������, � ����� ������� ������ � ������� ��������, ������� ����� ������ ��� �� ����.
���� � Java. ��������� � ����� ����������� ���� ������. ������ ����� ������������� ORM Hibernate.

## ������� ��������:
type=auto/user<br>
content-type=xml/html<br>
feed-tag=... [optional]<br>
feed-class=...<br>
channel-tag=... [optional]<br>
channel-className=... [optional]<br>
item-class=...<br>
item-tag=... [optional]<br>
title-class=...<br>
title-tag=...[optional]<br>
description-class=...<br>
description-tag=...[optional]<br>
publishedDate-class=... [optional]<br>
publishedDate-tag=... [optional]<br>
link-class=... [optional]<br>
link-tag=... [optional]<br>

### ������ (https://news.yandex.ru/):
type=user<br>
content-type=html<br>
feed-tag=div<br>
feed-class=rubric<br>
channel-tag=a<br>
channel-className=title<br>
item-class=story__content<br>
item-tag=div<br>
title-class=story__title<br>
title-tag=a<br>
description-class=story__text<br>
description-tag=div<br>

### ������ (https://news.mail.ru/politics/):
type=user<br>
content-type=html<br>
feed-tag=div<br>
feed-class=cols<br>
channel-tag=a<br>
channel-className=title<br>
item-class=newsitem<br>
item-tag=div<br>
title-class=newsitem__title<br>
title-tag=a<br>
description-class=newsitem__text<br>
description-tag=div<br>

### ������ (https://lenta.ru/rss/):
type=user<br>
content-type=xml<br>
channel-tag=channel<br>
item-tag=item<br>
title-tag=title<br>
description-tag=description<br>
publishedDate-tag=pubDate<br>
link-tag=link<br>

### ������ ����� ��� ������������ (������� ��������: type=auto):
https://snob.ru/rss/all <br>
http://www.pravda.com.ua/rss/