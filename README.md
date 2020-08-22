## これはなに？

sora tob sakanaファンによる同人サークル「星空の漁業組合」が頒布する『おさかな本できるかな？』に掲載された「歌詞に含まれる単語の重要度に着目した楽曲クラスタリングによる作品傾向の分析」の図表を抜粋したリポジトリです。

同人誌では紙面の都合上、図表の詳細が見えないためこのリポジトリにオリジナルを置いています。

## ファイルについて

- `appendix`

  - [`token_count.csv`](https://github.com/NaoY-2501/osakanabook_lyrics_clustering/blob/master/appendix/token_count.csv) : 単語の出現数の集計(出現数の降順)

- `sparse_pca`

  - [`sparse_pca.png`](https://github.com/NaoY-2501/osakanabook_lyrics_clustering/blob/master/sparse_pca/sparse_pca.png) : 次元削減結果(本誌図1)
  
  - [`sparse_pca_lyric_clusters.png`](https://github.com/NaoY-2501/osakanabook_lyrics_clustering/blob/master/sparse_pca/sparse_pca_lyric_clusters.png) : 次元削減結果をk平均法によりクラスタリングした結果(本誌図3)
  
  - [`sparse_pca_lyric_clusters_album.png`](https://github.com/NaoY-2501/osakanabook_lyrics_clustering/blob/master/sparse_pca/sparse_pca_lyric_clusters_album.png) : クラスタリング結果に楽曲の収録作品情報を付加した図(本誌図5)
  
  - [`sparse_pca_album_clusters.png`](https://github.com/NaoY-2501/osakanabook_lyrics_clustering/blob/master/sparse_pca/sparse_pca_album_clusters.png) : 収録作品ごとに各クラスタに分類された楽曲数をプロットした棒グラフ(本誌図7)
  
- `truncated_svd`

  - [`truncated_svd.png`](https://github.com/NaoY-2501/osakanabook_lyrics_clustering/blob/master/truncated_svd/truncated_svd.png) : 次元削減結果(本誌図2)
  
  - [`truncated_svd_lyric_clusters.png`](https://github.com/NaoY-2501/osakanabook_lyrics_clustering/blob/master/truncated_svd/truncated_svd_lyric_clusters.png) : 次元削減結果をk平均法によりクラスタリングした結果(本誌図4)
  
  - [`truncated_svd_lyric_clusters_album.png`](https://github.com/NaoY-2501/osakanabook_lyrics_clustering/blob/master/truncated_svd/truncated_svd_lyric_clusters_album.png) : クラスタリング結果に楽曲の収録作品情報を付加した図(本誌図6)
  
  - [`truncated_svd_album_clusters.png`](https://github.com/NaoY-2501/osakanabook_lyrics_clustering/blob/master/truncated_svd/truncated_svd_album_clusters.png) : 収録作品ごとに各クラスタに分類された楽曲数をプロットした棒グラフ(本誌図8)
