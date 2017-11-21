#####vim-easymotion
>     移动插件
>     junegunn/vim-plug
>     call plug#begin()
>     Plug 'mattn/emmet-vim'
>     call plug#end()

#####Emmet
>     #Emmet编辑html，css 
>     let g:user_emmet_expandabbr_key='<c-e>'
>     默认<c-y>

#####delimitMate
>     delimitMate 用于补全括号和引号
>     (换行不空行)
>     {
>     }

#####auto-pairs.vim
>     用于补全括号和引号(换行自动空一行)
>     {
>   
>     }

#####neocomplcache.vim
>      补全，缓存，对输过的检测显示补全词
>      let g:neocomplcache_enable_at_startup=1
>      设置启动vim启动插件
>      let g:neocomplcache_disable_auto_complete=1
>      设置不显示补全列表

#####repeat.vim
>      用"."重复上次执行的命令
>      rename.vim
>      重命名
>      nmap <F2> :Rename<Space>
>     

#####airline
>      http://blog.csdn.net/Demorngel/article/details/69054489￼
>      //nerdcommenter
>      为程序添加注释
>      使用：
>     1. \cc 注释当前行和选中行
>     2. \cn 没有发现和\cc有区别
>     3. \c<空格> 如果被选区域有部分被注释，则对被选区域执行取消注释操作，其它情况执行反转注释操作
>     4. \cm 对被选区域用一对注释符进行注释，前面的注释对每一行都会添加注释
>     5. \ci 执行反转注释操作，选中区域注释部分取消注释，非注释部分添加注释
>     6. \cs 添加性感的注释，代码开头介绍部分通常使用该注释
>     7. \cy 添加注释，并复制被添加注释的部分
>     8. \c$ 注释当前光标到改行结尾的内容
>     9. \cA 跳转到该行结尾添加注释，并进入编辑模式
>     10.\ca 转换注释的方式，比如： /**/和//
>     11.\cl \cb 左对齐和左右对其，左右对其主要针对/**/
>     12.\cu 取消注释

#####NerdTree
>     shift-R进行手动刷新目录
>     
>     
