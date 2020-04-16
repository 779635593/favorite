# composer 多线程+国内源

- ## 配置国内镜像

网址：``https://pkg.phpcomposer.com/``

全局安装命令：``composer config -g repo.packagist composer https://packagist.phpcomposer.com``
 
 
- ## 开启多线程 ``hirak/prestissimo``

github 地址：``https://github.com/hirak/prestissimo``

全局安装命令：``composer global require hirak/prestissimo``

- ## Composer源管理工具

GitHub地址：``https://github.com/slince/composer-registry-manager/blob/master/README-zh_CN.md``

全局安装命令：``composer global require slince/composer-registry-manager``

直接选择aliyun命令：``composer repo:use aliyun``

自己切换镜像: ``composer repo:use``
    
    Please select your favorite repository (defaults to composer) [composer]:
      [0 ] composer
      [1 ] aliyun
      [2 ] tencent
      [3 ] huawei
      [4 ] cnpkg
      [5 ] sjtug
      [6 ] phpcomposer
      [7 ] kkame
      [8 ] hiraku
      [9 ] webysther
      [10] solidworx
      [11] indra
      [12] varun

重置源命令：``composer repo:reset``