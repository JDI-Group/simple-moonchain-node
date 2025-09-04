# simple-mch-node

Detailed steps are here : https://doc.moonchain.com/docs/Testnet-Tutorials/Run-Moonchain-Supernode

1.在main分支执行git pull或者以其他方式更新下载仓库https://github.com/JDI-Group/simple-mch-node
2.复制.env.exmaple文件更名为.env，并且修改L1_ENDPOINT_HTTP,L1_ENDPOINT_WS环境变量分别为BNB Smart Chain网络的http rpc和rpc websocket链接

执行"docker compose --profile l2_execution_engine up  -d"命令

Steps:

On the main branch, run git pull or update the repository via other methods: https://github.com/JDI-Group/simple-mch-node.
Copy the .env.exmaple file and rename it to .env. Set L1_ENDPOINT_HTTP and L1_ENDPOINT_WS to the HTTP RPC and WebSocket RPC endpoints of the BNB Smart Chain, respectively.
Run the "docker compose --profile l2_execution_engine up  -d"command.
