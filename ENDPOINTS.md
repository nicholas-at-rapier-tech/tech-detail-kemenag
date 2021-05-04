# endpoints

## endpoints :: token
> - api/token/request
> - api/token/renewal/{token_access}
> - api/token/revoke/{token_access}

## endpoints :: user
> - api/user/register
> - api/user/login
> - api/user/logout/{token_session}

## endpoints :: news
> - api/news/add
> - api/news/list
> - api/news/list/top/{x}
> - api/news/list/sort/date/{desc/asc}
> - api/news/edit/{news_id}
> - api/news/delete/{news_id}
> - api/news/view/{news_id}

## endpoints :: opinion
> - api/opinion/add
> - api/opinion/list
> - api/opinion/list/top/{x}
> - api/opinion/list/sort/date/{desc/asc}
> - api/opinion/edit/{opinion_id}
> - api/opinion/delete/{opinion_id}
> - api/opinion/view/{opinion_id}

## endpoints :: renungan
> - api/renungan/add
> - api/renungan/list
> - api/renungan/list/top/{x}
> - api/renungan/list/sort/date/{desc/asc}
> - api/renungan/edit/{renungan_id}
> - api/renungan/delete/{renungan_id}
> - api/renungan/view/{renungan_id}

## endpoints :: majalah
> - api/majalah/add
> - api/majalah/list
> - api/majalah/list/top/{x}
> - api/majalah/list/sort/date/{desc/asc}
> - api/majalah/edit/{majalah_id}
> - api/majalah/delete/{majalah_id}
> - api/majalah/view/{majalah_id}

## endpoints :: data
> - api/data/add
> - api/data/list
> - api/data/list/top/{x}
> - api/data/list/sort/date/{desc/asc}
> - api/data/edit/{data_id}
> - api/data/delete/{data_id}
> - api/data/view/{data_id}

## endpoints :: reformasi_birokrasi
> - api/reformasi_birokrasi/add
> - api/reformasi_birokrasi/list
> - api/reformasi_birokrasi/list/top/{x}
> - api/reformasi_birokrasi/list/sort/date/{desc/asc}
> - api/reformasi_birokrasi/edit/{rb_id}
> - api/reformasi_birokrasi/delete/{rb_id}
> - api/reformasi_birokrasi/view/{rb_id}

## endpoints :: regulasi
> - api/regulasi/add
> - api/regulasi/list
> - api/regulasi/list/top/{x}
> - api/regulasi/list/sort/date/{desc/asc}
> - api/regulasi/edit/{regulasi_id}
> - api/regulasi/delete/{regulasi_id}
> - api/regulasi/view/{regulasi_id}

## endpoints :: pengumuman
> - api/pengumuman/add
> - api/pengumuman/list
> - api/pengumuman/list/top/{x}
> - api/pengumuman/list/sort/date/{desc/asc}
> - api/pengumuman/edit/{pengumuman_id}
> - api/pengumuman/delete/{pengumuman_id}
> - api/pengumuman/view/{pengumuman_id}

## endpoints :: mimbar_agama
> - api/mimbar_agama/add
> - api/mimbar_agama/list
> - api/mimbar_agama/list/top/{x}
> - api/mimbar_agama/list/sort/date/{desc/asc}
> - api/mimbar_agama/edit/{ma_id}
> - api/mimbar_agama/delete/{ma_id}
> - api/mimbar_agama/view/{ma_id}

## endpoints :: pelayanan_publik
> - api/pelayanan_publik/add
> - api/pelayanan_publik/list
> - api/pelayanan_publik/list/sort/date/{desc/asc}
> - api/pelayanan_publik/edit/{pelayanan_id}
> - api/pelayanan_publik/delete/{pelayanan_id}
> - api/pelayanan_publik/view/{pelayanan_id}

## endpoints :: pengaduan_masyarakat
> - api/pengaduan_masyarakat/add
> - api/pengaduan_masyarakat/list
> - api/pengaduan_masyarakat/list/sort/date/{desc/asc}
> - api/pengaduan_masyarakat/edit/{pengaduan_id}
> - api/pengaduan_masyarakat/delete/{pengaduan_id}
> - api/pengaduan_masyarakat/view/{pengaduan_id}

## endpoints :: contact_us
> - api/contact_us/add
> - api/contact_us/list
> - api/contact_us/list/sort/date/{desc/asc}
> - api/contact_us/edit/{contact_us_id}
> - api/contact_us/delete/{contact_us_id}
> - api/contact_us/view/{contact_us_id}

## endpoints :: company_profile_info
> - api/company_profile/edit
> - api/company_profile/view

## endpoints :: gallery
> - api/gallery/album/new
> - api/gallery/album/list
> - api/gallerr/album/add/{album_id}/{content_id}
> - api/gallery/album/view/{album_id}
> - api/gallery/album/delete/{album_id}

> - api/gallery/content/upload
> - api/gallery/content/view/{content_id}
> - api/gallery/content/delete/{content_id}

> - api/gallery/all/top/{x}
> - api/gallery/all/filter/{category_code}
> - api/gallery/video/top/{x}
> - api/gallery/video/filter/{category_code}
> - api/gallery/photo/top/{x}
> - api/gallery/photo/filter/{category_code}

## Endpoints :: infogragis
> - api/infografis/upload
> - api/infografis/view/{infografis_id}

> - api/infogragis/list/sort/{date}
> - api/infogragis/list/filter/{category_code}
