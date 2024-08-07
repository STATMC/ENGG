# sentiment.ipynb dosyası ve open_sentiment_news_data.ipynb

## --> scrape_all_sites fonksiyonunda df_data = yazan kısım siteleri çeken fonksiyonları çağırır.

## --> cekilen verilerin row row olacak şekilde sentiment analizi yapılır

## --> MongoDB den geçmişte çekilen veriler df olarak alınır ve yeni gelen verilerle birleştirilir. Drop_duplicate yaplılarak fazlalıklar silinir ve ardından database e tekrardan kayır edilir.


## --> open_sentiment_news_data.ipynb dosyasıyla databasedeki verler df olarak çağırılabilir.