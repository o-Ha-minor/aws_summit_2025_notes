CUS-02 日本語LLM構築メモ

タイトル
    国産LLM開発の現状と展望：Swallowプロジェクト

概要（要約）

    国立研究機関によるLLM開発では、継続事前学習（Continual Pre-Training）によってコストを抑えつつ、日本語に強いモデルの開発を進行中。Swallowモデル群は日本語に特化した分類器やWikiベースのQA強化などを通じ、GPT-4に迫る性能を目指す。

モデルと学習環境

    日本語・英語を混合し多言語的文脈理解を強化

    Reasoning強化のため、数学・コード領域にも注力

    P5インスタンスやAmazon SageMaker HyperPodにより高速学習を実現

    FSx for LustreとS3を使い分けてストレージコストを最適化

応用できそうなポイント

    日本語に強いモデルを業務QA、自治体・教育分野で活用可能

    SwallowCode/SwallowMathは公開済みで再現性あり（HFで利用可）

    RLHF（強化学習）やモード切替（think/chat）による柔軟な対話が可能

質問メモ

    Swallowモデルの更新頻度とサポート体制は？

    大規模LLMの運用コストと精度のバランス最適化の工夫は？

