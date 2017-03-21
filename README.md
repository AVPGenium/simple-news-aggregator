# simple-news-aggregator

������������, ���������� ������:
http://jquiz.azurewebsites.net/newsaggregator/
(������� ������������, ������� ����� �������� �� ��������� ���������� :)

## �������:
����� �������� ��������� ��������.
������������ ������ �� ���� ����� ���������� ����� ��� ��� RSS-����� � ������� �������� (������ ������� � �� ���������� ������������).
1. ��������� � ���. ��������� �� ����� ������������.
2. ������� � ����� �����, �� �������� ������ ������ ������, ��� ������� ��� ��� ���� ����. ������ ��� ����� ���� � �� rss.

���� ������ ���������� �������� ������������� ����������� ��������� � ����� �����.
� ������������ ���� ����������� ������������� ������ �������� �� ���� � ������ �� �� ��������� � ��������� �������.
� �������� ������� ��������� ���������� ��� ����� ��������� ����� �� �����.
��������� � �������� ��� ����������, � ����� ������� ������ � ������� ��������, ������� ����� ������ ��� �� ����.
���� � Java. ��������� � ����� ����������� ���� ������. ������ ����� ������������� ORM Hibernate.

## ������� ��������:
type=auto/user
content-type=xml/html
feed-tag=... [optional]
feed-class=...
channel-tag=... [optional]
channel-className=... [optional]
item-class=...
item-tag=... [optional]
title-class=...
title-tag=...[optional]
description-class=...
description-tag=...[optional]
publishedDate-class=... [optional]
publishedDate-tag=... [optional]
link-class=... [optional]
link-tag=... [optional]

### ������ (https://news.yandex.ru/):
type=user
content-type=html
feed-tag=div
feed-class=rubric
channel-tag=a
channel-className=title
item-class=story__content
item-tag=div
title-class=story__title
title-tag=a
description-class=story__text
description-tag=div

### ������ (https://news.mail.ru/politics/):
type=user
content-type=html
feed-tag=div
feed-class=cols
channel-tag=a
channel-className=title
item-class=newsitem
item-tag=div
title-class=newsitem__title
title-tag=a
description-class=newsitem__text
description-tag=div