# Dịch thuật Pro Git (Phiên bản 2)

Việc dịch thuật được quản lý một cách phi tập trung. Mỗi nhóm dịch thuật duy trì dự án của riêng mình. Mỗi bản dịch nằm trong kho lưu trữ (repository) riêng, nhóm Pro Git chỉ đơn giản là lấy các thay đổi và xây dựng chúng vào trang web https://git-scm.com khi sẵn sàng.

## Hướng dẫn chung về dịch thuật Pro Git

Pro Git là một cuốn sách về một công cụ kỹ thuật, do đó việc dịch nó khó hơn so với một bản dịch phi kỹ thuật.

Sau đây là các hướng dẫn để giúp bạn trên con đường của mình:
* Trước khi bắt đầu, hãy đọc toàn bộ sách Git Pro bằng tiếng Anh, để bạn nắm được nội dung và quen với văn phong được sử dụng.
* Đảm bảo bạn có kiến thức làm việc tốt về Git, để việc giải thích các thuật ngữ kỹ thuật là khả thi.
* Tuân thủ một văn phong và định dạng chung cho bản dịch.
* Hãy chắc chắn đọc và hiểu những điều cơ bản về [định dạng Asciidoc](https://docs.asciidoctor.org/asciidoc/latest/syntax-quick-reference/). Việc không tuân theo cú pháp asciidoc có thể dẫn đến các vấn đề với việc xây dựng/biên dịch các tệp pdf, epub và html cần thiết cho cuốn sách.

## Dịch sách sang ngôn ngữ khác

### Giúp đỡ một dự án hiện có

* Kiểm tra một dự án đã tồn tại trong bảng sau.
* Đi đến trang của dự án trên GitHub.
* Mở một issue, giới thiệu bản thân và hỏi bạn có thể giúp ở đâu.

| Ngôn ngữ | Trang GitHub |
| :------------- | :------------- |
| العربية | [progit2-ar/progit2](https://github.com/progit2-ar/progit2) |
| Беларуская | [progit/progit2-be](https://github.com/progit/progit2-be) |
| български език | [progit/progit2-bg](https://github.com/progit/progit2-bg) |
| Čeština | [progit-cs/progit2-cs](https://github.com/progit-cs/progit2-cs) |
| English | [progit/progit2](https://github.com/progit/progit2) |
| Español | [progit/progit2-es](https://github.com/progit/progit2-es) |
| فارسی | [progit2-fa/progit2](https://github.com/progit2-fa/progit2) |
| Français | [progit/progit2-fr](https://github.com/progit/progit2-fr) |
| Deutsch | [progit/progit2-de](https://github.com/progit/progit2-de) |
| Ελληνικά | [progit2-gr/progit2](https://github.com/progit2-gr/progit2) |
| Indonesian | [progit/progit2-id](https://github.com/progit/progit2-id) |
| Italiano | [progit/progit2-it](https://github.com/progit/progit2-it) |
| 日本語 | [progit/progit2-ja](https://github.com/progit/progit2-ja) |
| 한국어 | [progit/progit2-ko](https://github.com/progit/progit2-ko) |
| Македонски | [progit2-mk/progit2](https://github.com/progit2-mk/progit2) |
| Bahasa Melayu| [progit2-ms/progit2](https://github.com/progit2-ms/progit2) |
| Nederlands | [progit/progit2-nl](https://github.com/progit/progit2-nl) |
| Polski | [progit2-pl/progit2-pl](https://github.com/progit2-pl/progit2-pl) |
| Português (Brasil) | [progit/progit2-pt-br](https://github.com/progit/progit2-pt-br) |
| Русский | [progit/progit2-ru](https://github.com/progit/progit2-ru) |
| Slovenščina | [progit/progit2-sl](https://github.com/progit/progit2-sl) |
| Српски | [progit/progit2-sr](https://github.com/progit/progit2-sr) |
| Svenska | [progit2-sv/progit2](https://github.com/progit2-sv/progit2) |
| Tagalog | [progit2-tl/progit2](https://github.com/progit2-tl/progit2) |
| Türkçe | [progit/progit2-tr](https://github.com/progit/progit2-tr) |
| Українська| [progit/progit2-uk](https://github.com/progit/progit2-uk) |
| Ўзбекча | [progit/progit2-uz](https://github.com/progit/progit2-uz) |
| 简体中文 | [progit/progit2-zh](https://github.com/progit/progit2-zh) |
| 正體中文 | [progit/progit2-zh-tw](https://github.com/progit/progit2-zh-tw) |

### Bắt đầu một bản dịch mới

Nếu chưa có dự án cho ngôn ngữ của bạn, bạn có thể bắt đầu bản dịch của riêng mình.

Dựa trên công việc của bạn trên phiên bản thứ hai của cuốn sách, có sẵn [tại đây](https://github.com/progit/progit2). Để làm như vậy:
1. Chọn đúng [mã ISO 639](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) cho ngôn ngữ của bạn.
2. Tạo một [tổ chức GitHub](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/creating-a-new-organization-from-scratch), ví dụ: `progit2-[mã của bạn]` trên GitHub.
3. Tạo một dự án `progit2`.
4. Sao chép cấu trúc của progit/progit2 (dự án này) trong dự án của bạn và bắt đầu dịch.

### Cập nhật trạng thái bản dịch của bạn

Trên https://git-scm.com, các bản dịch được chia thành ba loại. Khi bạn đã đạt đến một trong các cấp độ này, hãy liên hệ với những người bảo trì của https://git-scm.com/ để họ có thể lấy các thay đổi.

| Thể loại | Hoàn thành |
| :------------- | :------------- |
| Đã bắt đầu dịch cho | Đã dịch phần giới thiệu, không có nhiều thứ khác. |
| Có sẵn các bản dịch một phần trong | đã dịch đến chương 6. |
| Có sẵn bản dịch đầy đủ trong | sách đã được dịch (gần như) đầy đủ. |

## Tích hợp liên tục với GitHub Actions

GitHub Actions là một dịch vụ [tích hợp liên tục](https://en.wikipedia.org/wiki/Continuous_integration) tích hợp với GitHub. GitHub Actions được sử dụng để đảm bảo rằng một pull-request không làm hỏng bản dựng hoặc quá trình biên dịch. GitHub Actions cũng có thể cung cấp các phiên bản đã biên dịch của cuốn sách.

Cấu hình cho GitHub Actions được chứa trong thư mục `.github/workflows`, và nếu bạn đưa nhánh `main` của kho lưu trữ gốc vào, bạn sẽ nhận được chúng miễn phí.
Tuy nhiên, nếu bạn đã tạo repo dịch của mình bằng cách _fork_ repo gốc, có một bước bổ sung bạn phải hoàn thành (nếu bạn không fork, bạn có thể bỏ qua phần này).
GitHub cho rằng các fork sẽ được sử dụng để đóng góp cho repo mà chúng được fork, vì vậy bạn sẽ phải truy cập tab "Actions" trên repo đã fork của mình và nhấp vào nút "I understand my workflows" để cho phép các action chạy.

## Thiết lập một chuỗi xuất bản cho sách điện tử

Đây là một nhiệm vụ kỹ thuật, vui lòng ping @jnavila để bắt đầu với việc xuất bản epub.

## Ngoài Pro Git

Dịch cuốn sách là bước đầu tiên. Sau khi hoàn thành, bạn có thể xem xét việc dịch giao diện người dùng của chính Git.

Nhiệm vụ này đòi hỏi kiến thức kỹ thuật về công cụ nhiều hơn so với cuốn sách. Hy vọng rằng, sau khi đã dịch toàn bộ nội dung cuốn sách, bạn có thể hiểu các thuật ngữ được sử dụng trong ứng dụng. Nếu bạn cảm thấy mình đủ khả năng kỹ thuật cho nhiệm vụ này, repo có [tại đây](https://github.com/git-l10n/git-po) và bạn chỉ cần làm theo [hướng dẫn](https://github.com/git-l10n/git-po/blob/master/po/README.md).

Tuy nhiên, hãy cẩn thận rằng

* bạn sẽ cần sử dụng các công cụ cụ thể hơn để quản lý các tệp po bản địa hóa (chẳng hạn như chỉnh sửa chúng bằng [poedit](https://poedit.net/)) và hợp nhất chúng. Bạn có thể cần phải biên dịch git để kiểm tra công việc của mình.
* cần có kiến thức cơ bản về cách hoạt động của việc dịch các ứng dụng, điều này khác biệt đáng kể so với việc dịch sách.
* dự án Git cốt lõi sử dụng các [thủ tục](https://github.com/git-l10n/git-po/blob/master/Documentation/SubmittingPatches) nghiêm ngặt hơn để chấp nhận các đóng góp, hãy chắc chắn tuân thủ chúng.