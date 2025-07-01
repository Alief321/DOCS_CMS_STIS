# Permission CMS

Pada CMS STIS yang baru terdapat mekanisme _Hybrid RBAC ABAC_ yang memungkinkan user memiliki hak akses yang bervariasi mengikuti rolenya dan mengikuti atribut khusus miliknya sendiri. Permission yang ada pada CMS STIS yang baru berkaitan dengan akses CRUD terhadap konten (_collection_) yang ada di CMS

## Daftar Konten (_Collection_)

Berikut adalah daftar konten yang ada di CMS Politeknik Statistika STIS beserta deskripsinya

| No  | Konten (_Collection_)   | Deskripsi                                                                |
| --- | ----------------------- | ------------------------------------------------------------------------ |
| 1   | Article                 | Pengelolaan Artikel STIS                                                 |
| 2   | Berita                  | Pengelolaan Berita STIS                                                  |
| 3   | Agenda                  | Pengelolaan Agenda STIS                                                  |
| 4   | Gallery                 | Pengelolaan Konten Galeri STIS                                           |
| 5   | UKM/UKK                 | Pengelolaan Konten UKM/UKK/Komunitas di Polsat STIS                      |
| 6   | Role                    | Pengelolaan Role yang ada di CMS                                         |
| 7   | User                    | Pengelolaan User yang ada di CMS                                         |
| 8   | Page                    | Pengelolaan Halaman yang ada di situs web                                |
| 9   | Konten Tentang STIS     | Pengelolaan isi konten Tentang STIS (_About STIS_) yang ada di situs web |
| 10  | Navigasi Header         | Pengelolaan dan penataan letak navigasi _header_ yang ada di situs web   |
| 11  | Navigasi Footer         | Pengelolaan dan penataan letak navigasi _footer_ yang ada di situs web   |
| 12  | FAQ                     | Pengelolaan konten _frequently asked questions_                          |
| 13  | Informasi publik Publik | Pengelolaan informasi publik publik                                      |
| 14  | Kategori                | Pengelolaan kategori konten                                              |
| 15  | Search Result           | Hasil indexing search untuk konten                                       |
| 16  | File                    | Pengelolaan dan manajemen File                                           |
| 17  | SSO                     | Pengelolaan Akun SSO                                                     |
| 18  | Folder                  | Pengelolaan Folder                                                       |

## Daftar Permission

Berikut adalah daftar permission yang terkait dengan konten (_collection_) yang ada di CMS STIS

# Permissions List

| No  | Konten (_Collection_) | Permission                 | Deskripsi                                                                |
| --- | --------------------- | -------------------------- | ------------------------------------------------------------------------ |
| 1   | article               | create-article             | membuat artikel                                                          |
| 2   | article               | read-article-for-verif     | membaca artikel yang sudah siap diverifikasi (sudah pernah difinalisasi) |
| 3   | article               | read-article-admin         | Menampilkan dan membolehkan user mengakses halaman daftar artikel        |
| 4   | article               | update-article             | mengupdate semua artikel                                                 |
| 5   | article               | update-own-article         | mengupdate artikel milik sendiri                                         |
| 6   | article               | delete-article             | menghapus semua artikel                                                  |
| 7   | article               | delete-own-article         | menghapus artikel milik sendiri                                          |
| 8   | article               | feedback-article           | dapat memberikan feedback artikel                                        |
| 9   | article               | read-own-article           | dapat membaca artikel yang dibuat sendiri                                |
| 10  | article               | verification-article       | memverifikasi artikel dan publish artikel                                |
| 11  | news                  | create-news                | membuat berita                                                           |
| 12  | news                  | read-news-admin            | menampilkan dan membolehkan user mengakses halaman daftar berita di CMS  |
| 13  | news                  | read-news-for-verif        | membaca berita yang sudah siap verifikasi (minimal 1x finalisasi)        |
| 14  | news                  | update-news                | mengupdate semua berita                                                  |
| 15  | news                  | update-own-news            | mengupdate berita milik sendiri                                          |
| 16  | news                  | delete-news                | menghapus semua berita                                                   |
| 17  | news                  | delete-own-news            | menghapus berita milik sendiri                                           |
| 18  | news                  | feedback-news              | memberikan/menulis feedback                                              |
| 19  | news                  | read-own-news              | dapat membaca berita buatan sendiri                                      |
| 20  | news                  | verification-news          | dapat verifikasi dan publikasi artikel                                   |
| 21  | agenda                | create-agenda              | membuat agenda                                                           |
| 22  | agenda                | read-agenda                | mengizinkan user mengakses halaman daftar agenda di CMS                  |
| 23  | agenda                | update-agenda              | mengupdate semua agenda                                                  |
| 24  | agenda                | update-own-agenda          | mengupdate agenda buatan sendiri                                         |
| 25  | agenda                | delete-agenda              | menghapus agenda                                                         |
| 26  | agenda                | delete-own-agenda          | menghapus agenda buatan sendiri                                          |
| 27  | agenda                | read-own-agenda            | membaca agenda buatan sendiri                                            |
| 28  | agenda                | feedback-agenda            | memberikan feedback pada agenda                                          |
| 29  | agenda                | verification-agenda        | dapat verifikasi dan publikasi agenda                                    |
| 30  | agenda                | read-agenda-for-verif      | membaca agenda siap verifikasi (minimal sudah 1x finalisasi)             |
| 31  | gallery               | create-gallery             | membuat galeri                                                           |
| 32  | gallery               | read-gallery               | mengizinkan user mengakses halaman gallery di cms                        |
| 33  | gallery               | update-gallery             | mengupdate semua gallery                                                 |
| 34  | gallery               | update-own-gallery         | mengupdate galeri buatan sendiri                                         |
| 35  | gallery               | delete-gallery             | menghapus semua galeri                                                   |
| 36  | gallery               | delete-own-gallery         | menghapus gallery buatan sendiri                                         |
| 37  | gallery               | read-own-gallery           | membaca galeri buatan sendiri                                            |
| 38  | gallery               | feedback-gallery           | memberikan komentar pada galeri                                          |
| 39  | gallery               | verification-gallery       | memverifikasi galeri dan publikasi                                       |
| 40  | gallery               | read-gallery-for-verif     | membaca galeri siap verifikasi (minimal 1x finalisasi)                   |
| 41  | achievement           | create-achievement         | membuat achievement                                                      |
| 42  | achievement           | read-achievement-for-verif | membaca achievement siap verifikasi (minimal sudah 1x finalisasi)        |
| 43  | achievement           | read-achievement           | menampilkan dan membolehkan user mengakses halaman daftar achievement    |
| 44  | achievement           | update-achievement         | mengupdate semua achievement                                             |
| 45  | achievement           | update-own-achievement     | mengupdate achievement milik sendiri                                     |
| 46  | achievement           | delete-achievement         | menghapus semua achievement                                              |
| 47  | achievement           | delete-own-achievement     | menghapus achievement milik sendiri                                      |
| 48  | achievement           | feedback-achievement       | memberikan feedback pada achievement                                     |
| 49  | achievement           | read-own-achievement       | membaca achievement buatan sendiri                                       |
| 50  | achievement           | verification-achievement   | memverifikasi dan publikasi achievement                                  |
| 51  | ukm                   | create-ukm                 | membuat ukm                                                              |
| 52  | ukm                   | read-ukm                   | menampilkan dan membolehkan user mengakses halaman daftar ukm di CMS     |
| 53  | ukm                   | update-ukm                 | mengupdate semua ukm                                                     |
| 54  | ukm                   | delete-ukm                 | menghapus semua ukm                                                      |
| 55  | ukm                   | feedback-ukm               | memberikan feedback pada ukm                                             |
| 56  | ukm                   | read-all-ukm               | membaca semua ukm                                                        |
| 57  | ukm                   | verification-ukm           | memverifikasi dan publikasi ukm                                          |
| 58  | role                  | create-role                | membuat role                                                             |
| 59  | role                  | read-role-admin            | menampilkan dan mengakses halaman daftar role di CMS                     |
| 60  | role                  | read-role                  | membaca role                                                             |
| 61  | role                  | update-role                | mengupdate role                                                          |
| 62  | role                  | delete-role                | menghapus role                                                           |
| 63  | user                  | create-user                | membuat user                                                             |
| 64  | user                  | read-user-admin            | menampilkan dan mengakses halaman daftar user di CMS                     |
| 65  | user                  | read-user                  | membaca user                                                             |
| 66  | user                  | update-user                | mengupdate user                                                          |
| 67  | user                  | delete-user                | menghapus user                                                           |
| 68  | page                  | create-page                | membuat halaman (page)                                                   |
| 69  | page                  | read-page                  | menampilkan dan mengakses halaman daftar page di CMS                     |
| 70  | page                  | update-page                | mengupdate semua page                                                    |
| 71  | page                  | delete-page                | menghapus page                                                           |
| 72  | page                  | read-own-page              | membaca page buatan sendiri                                              |
| 73  | page                  | read-all-page              | membaca semua page                                                       |
| 74  | about                 | create-about               | membuat about                                                            |
| 75  | about                 | read-about                 | menampilkan dan mengakses halaman daftar about di CMS                    |
| 76  | about                 | update-about               | mengupdate about                                                         |
| 77  | about                 | delete-about               | menghapus about                                                          |
| 78  | header                | create-header              | membuat header                                                           |
| 79  | header                | read-header                | menampilkan dan mengakses halaman daftar header di CMS                   |
| 80  | header                | update-header              | mengupdate header                                                        |
| 81  | header                | delete-header              | menghapus header                                                         |
| 82  | footer                | create-footer              | membuat footer                                                           |
| 83  | footer                | read-footer                | menampilkan dan mengakses halaman daftar footer di CMS                   |
| 84  | footer                | update-footer              | mengupdate footer                                                        |
| 85  | footer                | delete-footer              | menghapus footer                                                         |
| 86  | faq                   | create-faq                 | membuat faq                                                              |
| 87  | faq                   | read-faq                   | menampilkan dan mengakses halaman daftar faq di CMS                      |
| 88  | faq                   | update-faq                 | mengupdate faq                                                           |
| 89  | faq                   | delete-faq                 | menghapus faq                                                            |
| 90  | information           | create-information         | membuat informasi publik                                                 |
| 91  | information           | read-information           | menampilkan dan mengakses halaman daftar informasi publik di CMS         |
| 92  | information           | update-information         | mengupdate semua informasi publik                                        |
| 93  | information           | update-own-information     | mengupdate informasi publik milik sendiri                                |
| 94  | information           | delete-information         | menghapus semua informasi publik                                         |
| 95  | information           | delete-own-information     | menghapus informasi publik milik sendiri                                 |
| 96  | information           | read-own-information       | membaca informasi publik buatan sendiri                                  |
| 97  | information           | feedback-information       | memberikan feedback pada informasi publik                                |
| 98  | information           | verification-information   | memverifikasi dan publikasi informasi publik                             |
| 99  | information           | read-information-for-verif | membaca informasi publik siap verifikasi (minimal sudah 1x finalisasi)   |
| 100 | category              | create-category            | membuat kategori                                                         |
| 101 | category              | read-category              | menampilkan dan mengakses halaman daftar kategori di CMS                 |
| 102 | category              | update-category            | mengupdate kategori                                                      |
| 103 | category              | delete-category            | menghapus kategori                                                       |
| 104 | redirects             | create-redirects           | membuat redirect                                                         |
| 105 | redirects             | read-redirects             | menampilkan dan mengakses halaman daftar redirect di CMS                 |
| 106 | redirects             | update-redirects           | mengupdate redirect                                                      |
| 107 | redirects             | delete-redirects           | menghapus redirect                                                       |
| 108 | search                | read-search                | mengakses halaman pencarian di CMS                                       |
| 109 | file                  | create-file                | mengunggah file                                                          |
| 110 | file                  | read-file                  | membaca/menampilkan file di halaman admin                                |
| 111 | file                  | update-file                | mengupdate semua file                                                    |
| 112 | file                  | delete-file                | menghapus semua file                                                     |
| 113 | file                  | delete-own-file            | menghapus file milik sendiri                                             |
| 114 | file                  | update-own-file            | mengupdate file milik sendiri                                            |
| 115 | sso                   | read-sso                   | mengakses pengaturan SSO di CMS                                          |
| 116 | sso                   | delete-sso                 | menghapus data akun SSO                                                  |
| 117 | folder                | create-folder              | membuat folder                                                           |
| 118 | folder                | read-folder                | mengakses daftar folder di halaman admin                                 |
| 119 | folder                | update-folder              | mengupdate folder                                                        |
| 120 | folder                | delete-folder              | menghapus folder                                                         |
