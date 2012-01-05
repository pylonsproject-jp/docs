============================
Tutorial: Pyramid for Humans(和訳)
============================

Pyramidは、PylonsやZopeのコミュニティにいる人たちのための「高速で、モダンで、軽量なウェブフレームワーク」です。
もし、あなたが完全なCMSをそのまま使いたいのではなく、Ploneと同じ技術を用いたウェブアプリを、
いちからフルスクラッチで作りたいのであれば、Pyramidはそれを実現させてくれます。

.. Pyramid has emerged as a fast, modern, lightweight web
.. framework for the Pylons and Zope communities. When you just need a
.. web app, and not a full CMS, Pyramid lets you retain many of the same
.. Plone technologies or start from scratch.

このチュートリアルは、実際の開発を行う際にみな使うと思う基礎的な機能について、ハンズオン形式で広く浅く紹介します。
エキスパートではない方々のために、少しだけペースは早いですが、楽しんでもらえるよう心がけてつくりました。

.. This hands-on tutorial covers a little about a lot: practical
.. introductions to the most common facilities.  Fun, fast-paced, and
.. most certainly not aimed at experts.

Approach
========

このチュートリアルは、いくつかのパートに分けられています。最初のパートは、ダミーのUI/UXを作成するパートです。
また、各パートはさらに小さないくつかのステップに分けられていて、その分けられた各ステップごとに、重要なコンセプトを少しずつ紹介していきます。
こうして、動くコードを段階的に成長させていく形式をとっています。

.. The tutorial is broken into major areas, starting with constructing a
.. dummy UI/UX. Each major area is then broken into a series of steps in
.. which a very small number of concepts is introduced in each step.
.. Working code is gradually built up.

このチュートリアルは、「複数の会社が参加するプロジェクトが複数あるという状況を管理するマネジメントシステムを作る」
というシナリオでやっていきます。また、ディスパッチの方法としてtraversalを使い、データの永続化にはZODBを使うことにしました。

.. .. 基本基盤としてtraversalとZODBを使うことにしました。 どう考えても分かんないし。

.. As explained in the scenario, the sample application is a project 
.. management system for multiple companies with multiple projects. We
.. chose traversal and ZODB as the primary architecture for this tutorial.

Contents
========


.. toctree::
    :maxdepth: 3

    scenario
    setup
    creatingux/index
    resources/index
    forms_schemas/index

In-Progress Contents
====================

The following sections still need re-writing after feedback at the
conference:

.. toctree::
    :maxdepth: 3

    security/index
    zodb/index
    catalog/index
