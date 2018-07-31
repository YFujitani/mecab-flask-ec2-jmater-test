# mecab-flask-ec2-jmater-test

ec2のflusk、mecabの負荷テストスクリプト



下記をテスト対象のサーバに応じて適宜編集
```
<stringProp name="HTTPSampler.domain">localhost</stringProp>
<stringProp name="HTTPSampler.port">5000</stringProp>
<stringProp name="HTTPSampler.protocol">http</stringProp>
```


下記はパラメータの外部ファイルのパスに応じて適宜編集
```
<stringProp name="Argument.value">{&#xd;
	&quot;input_text&quot;: &quot;${__StringFromFile(/Users/yoshimasa/Downloads/apache-jmeter-4.0/bin/input_text.txt)}&quot;	&#xd;
}</stringProp>
```
