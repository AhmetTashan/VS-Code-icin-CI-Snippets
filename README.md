## VS Code için CodeIgniter 3 Snippets

Bu repo içerisinde  **ci-snippets2** ekletisini kendi kullandığım şekle büründürdüm. Sizde kullanmak isterseniz, VS Code'da **ci-snippets2** uygulamasını kurup **snippets** [dosyasını değiştirmeniz](#dosya-değiştirme) yeterli olacaktır.

Bunun için https://snippet-generator.app/ adresinden biraz destek aldığım söylenebilir.

#### Snippets Tablosunun içeriği

| Prefix           | Açıklama                     |
| ---------------- | ---------------------------- |
| ci_base          |                              |
| ciline           | Yorum Satırı                 |
| ci_start         |                              |
| **controller**   | **Controller Sayfası**       |
| _cookie          |                              |
| **crud**         | **Örnek dört temel işlem**   |
| db_affected      |                              |
| db_delete        |                              |
| db_from          |                              |
| db_get           |                              |
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
// $CURRENT_YEAR-$CURRENT_MONTH-$CURRENT_DATE
/*
 * çıktı: 2019-12-05
 */
```

#### Dosya Değiştirme

C:\Kullanıcılar\{kullanici_adi}\\.vscode\extensions\anish-m.ci-snippets2-1.0.0\snippets

içerisindeki **snippets.json** dosyasını değiştirilmesi yeterli olacaktır.



DİPNOT: `Tab` ayarı için  **Editor: Insert Spaces** ayarını `false` yap
