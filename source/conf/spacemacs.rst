.. 配置 spacemacs

配置 spacemacs
====================================

``spacemacs`` 是 vim 与 emacs 的完美结合体，对于习惯了 vim 的，又想有更强大的扩展功能的可以选用。

在 ``Mac OSX`` 安装好 Homebrew 后，可通过命令如下：

.. code:: bash

  brew cask install emacs

下载最新的 ``spacemacs``

.. code:: bash

  git clone https://github.com/syl20bnr/spacemacs ~/.emacs.d

配置 ``.spacemacs``, 修改如下：

.. code:: lisp

  ;; 使用 http 来下载
  dotspacemacs-elpa-https nil
