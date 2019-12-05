## VS Code için CodeIgniter 3 Snippets

Bu repo içerisinde  **ci-snippets2** ekletisini kendi kullandığım şekle büründürdüm. Sizde kullanmak isterseniz, VS Code **ci-snippets2** uygulamasını kurup kendinize göre ayarlaya bilirsiniz.

Bunun için https://snippet-generator.app/ adresinden biraz destek aldığım söylenebilir.

#### Snippets Tablosunun içeriği

| Prefix           | Açıklama                     |
| ---------------- | ---------------------------- |
| ci_base          | base_url                     |
| ciline           | Yorum Satırı                 |
| ci_start         | Başlangıç class              |
| **controller**   | **Controller Sayfası**       |
| _cookie          | CI - Cookie                  |
| **crud**         | **Örnek dört temel işlem**   |
| db_affected      | CI - db etkilenen satır      |
| db_delete        | CI - db kayıt silme          |
| db_from          | CI - db tablo adı            |
| db_get           | CI - db get()                |
| db_group         |                              |
| db_insert        |                              |
| db_insert_id     |                              |
| db_join          |                              |
| db_last          |                              |
| db_limit         |                              |
| db_num_fields    |                              |
| db_num_rows      |                              |
| db_order         |                              |
| db_result        |                              |
| db_result_array  |                              |
| db_row           |                              |
| db_row_array     |                              |
| db_select        |                              |
| db_truncate      |                              |
| db_update        |                              |
| db_where         |                              |
| echopre          | Pre tagı içerisinde yazdırma |
| email            |                              |
| _get             |                              |
| **get_instance** | **$ci = =& get_instance();** |
| _get_post        |                              |
| ip_address       |                              |
| is_ajax          |                              |
| load_helper      |                              |
| load_library     |                              |
| load_model       |                              |
| load_view        |                              |
| log              |                              |
| **model**        | **Model Sayfası**            |
| **output_json**  | **verileri json çıktı alır** |
| pagination       | tüm sayfalama ayarları       |
| _post            |                              |
| **redirect**     | **yönlendirme**              |
| set_json         | sayfa yapısı json            |
| site             | site_uri                     |
| **this**         | **$this->**                  |
| **uri_segment**  |                              |
| user_agent       |                              |

 1.20 numaralı [VS Kod sürümünden itibaren](https://code.visualstudio.com/updates/v1_20#_more-snippet-variables) , Snippet'ler şu tarih ve saat eklene bilmektedir. Örnek kullanım;

```js
/*
 * $CURRENT_YEAR-$CURRENT_MONTH-$CURRENT_DATE
 * 
 * cıktı: 2019-12-05
 */
```

Dosya Yolu 

C:\Kullanıcılar\{kullanici_adi}\\.vscode\extensions\anish-m.ci-snippets2-1.0.0\snippets

içerisindeki **snippets.json** dosyasını değiştirilmesi yeterli olmaktadır.



DİPNOT: `Tab` ayarı için  **Editor: Insert Spaces ** ayarını `false`yap
