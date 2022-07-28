# Minima
## How to use:

### Setting up
* git clone https://github.com/piercezhangx/minima.git
* cd minima
* npm install
* replace IP and UUID from nodes.txt with your node IP and minima account node ID(If multiple Node IDs, put on the new line)
  * Eg:
~~~
127.0.0.1:c6f4f6fb-b231-4213-bdab-026fbe06bdc0
127.0.0.1:c6f4f6fb-b231-4213-bdab-026fbe06bdc1
127.0.0.1:c6f4f6fb-b231-4213-bdab-026fbe06bdc2
127.0.0.1:c6f4f6fb-b231-4213-bdab-026fbe06bdc3
...
~~~

## Auto Ping
* `node minima.js`


---
## 设置
* git clone https://github.com/piercezhangx/minima.git
* cd minima
* npm install

## 添加节点
在nodes.txt里面添加你的节点IP和Node ID. 格式是IP:NODE_ID
例如:
~~~
127.0.0.1:c6f4f6fb-b231-4213-bdab-026fbe06bdc0
127.0.0.1:c6f4f6fb-b231-4213-bdab-026fbe06bdc1
127.0.0.1:c6f4f6fb-b231-4213-bdab-026fbe06bdc2
127.0.0.1:c6f4f6fb-b231-4213-bdab-026fbe06bdc3
...
~~~

## 运行自动ping的脚本
`node minima.js`

这个脚本自动每小时ping一次(你可以自己调整一下间隔)

每天UTC 0点时间，账号会获得1个reward
