.. vim: syntax=rst

.. _about_embedfire:

EMAN_EXEC_MANAGER.
==============
  EMAN_EXEC_MANAGER 工具系列：
    - eman_exec
    - eman_server
    - eman_client
           EasyView Ic Design @copyright
----------------------------------
  EMAN_EXEC_MANAGER 继承synopsys的eman exec manager 执行管理器设计理念，除了代码覆盖率分析不能支持意外，除此之外所有的功能可以自定义进行支持，另外关于eman verif ai部分
也有所实现。
验证目前经历了三个阶段:
  directed-test Drive：直接给dut施加激励，然后判断DUT输出是否正确，来验证DUT的各个功能，但是带来的问题，验证不能完备，会遗漏很多隐藏的bug。
  coverage drive：基于coverage，施加激励，然后最后收集coverage，来判断功能验证是否完备，但是带来的问题是，编写coverage可能会遗漏，造成验证不能完备，并且很难去预估验证是否完成。
  metric drive：是目前新提出的功能验证方法学。基于验证计划的各个feature，施加激励，最后收集各个feature的metric，反标到验证计划中，得到可视化结果，从而确定验证是否完备。
  eman_exec目前以功能覆盖率为goal进行收敛，在test 数据和cov 数据、种子数据管理基础之上，采用机器学习指定覆盖率优化目标，达到case 资源利用减少，以及约束空间下种子探索空间，自动增加种子，生成测试。

个人联系方式
----------------------------
- github主页：xxxxxx
- gitee主页： xxxxxx
- 淘宝： xxxxxx
- 邮箱： 190383666@qq.com
- 电话： 18079147092



