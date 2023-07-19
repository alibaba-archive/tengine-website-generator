## 文档

Tengine完全兼容Nginx，因此可以参照Nginx的方式来配置Tengine。
我们在此只列出Tengine中值得注意的功能。 
关于详细的Tengine的相对于Nginx的差别，可以访问[变更列表](changelog_cn.html)。

### 使用

*   [编译和安装](document_cn/install_cn.html)
*   [命令行参数](document_cn/commandline_cn.html)

### 模块文档

*   [主功能](document_cn/core_cn.html)
*   [HTTP核心模块](document_cn/http_core_cn.html)
*   [XQUIC模块](document_cn/xquic_cn.html)
*   [XUDP模块](document_cn/xudp_cn.html)
*   [动态加载模块功能](document_cn/dso_cn.html)(已废弃)
*   [Dyups模块](document_cn/http_dyups_cn.html)
*   [SPDY模块功能](document_cn/ngx_http_spdy_module_cn.html)(已废弃)
*   [独立进程模块功能](document_cn/proc_cn.html)
*   [backtrace模块功能](document_cn/http_backtrace_cn.html)
*   [concat模块功能](document_cn/http_concat_cn.html)
*   [trim filter模块功能](document_cn/http_trim_filter_cn.html)
*   [Upstream域名解析模块功能](document_cn/http_upstream_dynamic_cn.html)
*   [headers模块功能](document_cn/http_headers_cn.html)
*   [footer filter模块功能](document_cn/http_footer_filter_cn.html)
*   [limit_req模块功能](document_cn/http_limit_req_cn.html)
*   [limit upstream tries功能](document_cn/ngx_limit_upstream_tries_cn.html)
*   [log模块功能](document_cn/http_log_cn.html)
*   [reqstat模块功能](document_cn/http_reqstat_cn.html)
*   [lua模块(v0.10.14rc4)](https://github.com/chaoslawful/lua-nginx-module/blob/master/README.markdown)
*   [ssl模块功能](document_cn/http_ssl_cn.html)
*   [stub_status模块功能](document_cn/http_stub_status_cn.html)
*   [TFS模块功能](https://github.com/alibaba/nginx-tfs/blob/master/ReadMe.markdown)
*   [sysguard模块功能](document_cn/http_sysguard_cn.html)
*   [一致性hash模块功能](document_cn/http_upstream_consistent_hash_cn.html)
*   [session_sticky模块功能](document_cn/http_upstream_session_sticky_cn.html)
*   [健康检查模块功能](document_cn/http_upstream_check_cn.html)
*   [后端长连接超时功能](document_cn/http_upstream_keepalive_timeout_cn.html)
*   [变量](document_cn/variables_cn.html)
*   [debug pool模块](document_cn/ngx_debug_pool_cn.html)
*   [slab stat模块](document_cn/ngx_slab_stat_cn.html)
*   [异步openssl模块](document_cn/ngx_http_ssl_asynchronous_mode_cn.html)
*   [proxy connect模块](document_cn/proxy_connect_cn.html)
*   [异步日志和自动回滚模块](document_cn/ngx_log_pipe_cn.html)
*   [Stream 模块支持server name](document_cn/stream_sni_cn.html)
*   [支持后端Dubbo协议](document_cn/ngx_http_dubbo_module_cn.html)
*   [upstream支持VNSWRR高效负载均衡算法](document_cn/ngx_http_upstream_vnswrr_module_cn.html)

### 资料下载

*   [《淘宝网Nginx定制开发实战》](download/nginx@taobao.pdf)（Velocity China 2011.12）</a>
*   [《淘宝网Nginx应用、定制与开发实战》](download/taobao_nginx_2012_06.pdf)（华东运维技术大会 2012.06）</a>
*   [《淘宝Tengine--易运维的高性能Nginx服务器》](download/programmer-201209-Tengine.pdf)（《程序员》杂志, 2012年9月刊登）</a>

### Nginx官方文档中文版

*   [Nginx文档](nginx_docs/cn/)
