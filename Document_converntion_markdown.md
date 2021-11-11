# Tc in linux
**Note : help to control flow of packet with some special technical** 

* Throttling Network data
* Queueing 
* Dropping the occasional packet

```
GOAL: Get the highest throughput with lowest latecy 
```

## Main
* **Configuration the tree (per interface) of behaviours** 
* **Traffic enters this tree at the root and is routed according to filtering until it ends up at a leaf of the tree**

## Filter
** Must have a classifier, which is used to select packet (and typically route it to specific qdisc, may have a policer which can do things like "if exceeding this rate drop a packet"  - Seems rarely used , presumably too heavy-handed) 



**We have most common classifier types :
* u32 
```
Can inspect all of a packet
```
* fw
```
useful when you use iptables to mark the packets metadata
```
* tcindex
```
useful only for DSMARK
```
* route, rsvp, rsvp6

# TEST TABLE CONVENTION

| Plugin | Readme |
| ------ | ------ |
| Dropbox | [This is the first document for Dropbox][1] |
| Github | [This is the second document for Github][2] |
| Google Drive | [This is third document for Google Drive][3] |



[1]: https://www.dropbox.com/
[2]: https://github.com/
[3]: https://www.google.com.vn/


## Hightlight
*Phần này sẽ mô tả chi tiết cho hightlight theo định danh dữ liệu* 
**Phần này sẽ mô tả chi tiết cho hightlight theo định danh dữ liệu**
***Phần này sẽ mô tả chi tiết cho hightlight theo định danh dữ liệu***

` phần này inline code `

```python
	print("Say hello")
```

```c
	#include <stdio.h>
	#include <conio.h>
```




Các cú pháp thường dùng:

Tiêu đề:
#
##
###
Bôi đậm và in nghiêng
_  in nghiêng
*	in nghiêng

**	bôi đậm
-- bôi đậm

*** vừa in nghiêng và vừa bôi đậm
___ vừa in nghiêng và vừa bôi đậm

Gạch ngang
~~conetnt~~

Link 
[Title] (Link to document "describe (if you have)")


Hình ảnh
![Title] (Link to image "describe (if you have)")

Định dạng danh sách
	* content
		* content

	1. content
	2. content
	3. content

Trích dẫn
	> content

Thưc hiện đánh link tài liệu tham khảo 
	[content1][1] 
	[content2][2]

	[1]: Link to document
	[2]: Link to document


Bảng
	| Column1 | Column2|
	|-------- |--------|
	|content1|content2|
	|content1|content2|


Emoji
	:smile

Chú thích
	Content [^1]
	[^1]: Content

Mã code
	The `let` keyword
	```
	content
	```


# 
