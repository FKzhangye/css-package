# css_components
css�������

## CSS�������ʹ��˵��

��HTML�ĵ����������Ӧ��HTML�ṹ��ǩ������class��������������CSS�ļ����ɣ�

```
<link rel="stylesheet" href="components.css">
```

- input�����
`HTML`��
```
<input type="text" class="input-text-box" placeholder="����">
```

- button
`����button��ɫ��ť`��

```
HTML��
<button class="btn-set-color">Yes!</button>
���İ�ť��ɫֻ����background-color:;�����Ǽ��ɡ�
���İ�ť��С��ֱ�Ӹ��������С
��������button�����䰴ť��
Ĭ����ʽ
��껮��ʱЧ��
HTML��
<div class="btn-set-many">
    <button class="btn left">Left</button>
    <button class="btn middle">Middle</button>
    <button class="btn right">Right</button>
</div>
��ӻ�ɾ����ťֱ����HTML�ṹ�и��ı�ǩ�Ķ��١�
���İ�ť��Сֱ�Ӹ��������С��
���İ�ť������ɫ��

?��ѡ��

HTML��
<input type="checkbox" id="watermelon" name="checkbox"/>
<label for="watermelon">����</label>
<input type="checkbox" id="grape" name="checkbox"/>
<label for="grape">����</label>
ע�⣺һ��input������id��һ��label��.
���ĸ�ѡ���С�������������С��
����ѡ�к�ѡ�����ɫ����ɫ��Ҫ��rgba��д����
.customize-checkbox:checked+label::before{
    content:'\2713';
    background: rgba(150, 197, 47, 0.49);
}
?��ѡ

HTML��
<input type="radio" id="radio" name="radio" class="radio"/>
<label for="radio">���׷�</label>
<input type="radio" id="bbb" name="radio" class="radio"/>
<label for="bbb">����</label>
���ĵ�ѡ��Ĵ�С��ѡ�е���ɫͬ��ѡ����ͬ��
?������
����������

HTML:
<div class="dropdown">
    <div class="dropdown-toggle">
        dropdown
        <span class="caret"></span>
    </div>
    <ul class="dropdown-menu">
        <li><a href="#">Action</a></li>
        <li><a href="#">Action</a></li>
        <li><a href="#">Another action</a></li>
        <li><a href="#">Something else here</a></li>
        <li><a href="#">Separated link</a></li>
    </ul>
</div>
���ָ���������

ֻ����dropdown-menu�мӣ�
<li class="dividing-line"></li>
HTML:
<div class="dropdown">
    <div class="dropdown-toggle">
        dropdown
        <span class="caret"></span>
    </div>
    <ul class="dropdown-menu">
        <li><a href="#">Action</a></li>
        <li><a href="#">Action</a></li>
        <li><a href="#">Another action</a></li>
        <li class="dividing-line"></li>
        <li><a href="#">Something else here</a></li>
        <li><a href="#">Separated link</a></li>
    </ul>
</div>
?�����Ӽ�
�����Ӽ������䣩��

HTML:
<div class="quantity-add-less-classic">
    <button class="less">-</button>
    <input type="text" class="quantity-input-num" value="1">
    <button class="add">+</button>
</div>
�����Ӽ�������)��

HTML:
<div class="quantity-add-less-Separation">
    <input type="text" class="quantity-input-num" value="1">
    <div class="add-less">
        <button class="add">+</button>
        <button class="less">-</button>
    </div>
</div>
�����Ӽ�(�ָ�)��

HTML:
<div class="quantity-add-less-Separation quantity-add-less-spacing">
    <input type="text" class="quantity-input-num" value="1">
    <div class="add-less">
        <button class="add">+</button>
        <button class="less">-</button>
    </div>
</div>
```
