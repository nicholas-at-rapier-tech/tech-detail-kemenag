# Tables


## Table :: berita
> - id
> - title
> - url
> - category
> - views
> - content
> - writer
> - editor
> - source
> - create_at
> - create_by
> - update_at
> - update_by


## Table :: berita_img
> - id
> - berita_id
> - remark
> - base64_img
> - url_path
> - create_at
> - create_by
> - update_at
> - update_by


## Table :: opini
> - id
> - title
> - url
> - category
> - views
> - content
> - writer
> - editor
> - source
> - create_at
> - create_by
> - update_at
> - update_by


## Table :: opini_img
> - id
> - opini_id
> - remark
> - base64_img
> - url_path
> - create_at
> - create_by
> - update_at
> - update_by


## Table :: renungan
> - id
> - title
> - url
> - category
> - views
> - content
> - writer
> - editor
> - source
> - create_at
> - create_by
> - update_at
> - update_by


## Table :: renungan_img
> - id
> - renungan_id
> - remark
> - base64_img
> - url_path
> - create_at
> - create_by
> - update_at
> - update_by


## Table :: pengumuman
> - id
> - title
> - kategori
> - content
> - release_date
> - url
> - create_at
> - create_by
> - update_at
> - update_by

## Table :: pengumuman_img
> - id
> - pengumuman_id
> - remark
> - base64_img
> - url_path
> - create_at
> - create_by
> - update_at
> - update_by


## Table :: mimbar_agama
> - id
> - title
> - kategori
> - content
> - release_date
> - url
> - create_at
> - create_by
> - update_at
> - update_by

## Table :: mimbar_agama_img
> - id
> - mimbar_agama_id
> - remark
> - base64_img
> - url_path
> - create_at
> - create_by
> - update_at
> - update_by

## Table :: infografis
> - id
> - title
> - kategori
> - release_date
> - create_at
> - create_by
> - update_at
> - update_by

## Table :: infografis_img
> - id
> - infografis_id
> - sequence
> - remark
> - base64_img
> - url_path
> - create_at
> - create_by
> - update_at
> - update_by


## Table :: gallery_album
> - id
> - title
> - remark
> - create_at
> - create_by
> - update_at
> - update_by

## Table :: gallery
> - id
> - remark
> - type (video,photo)
> - extension
> - album_id
> - url_path_file
> - create_at
> - create_by
> - update_at
> - update_by


## Table :: info_footer
> - id
> - company
> - base64_logo
> - address
> - email 
> - phone
> - latitude
> - longitude
> - base64_qrcode
> - facebook
> - twitter
> - whatsapp
> - instagram
> - youtube
> - copyright
> - create_at
> - create_by
> - update_at
> - update_by


## Table :: pelayanan_publik
> - id
> - title
> - remark
> - base64_image
> - url_path_image
> - create_at
> - create_by
> - update_at
> - update_by

## Table :: pengaduan_masyarakat
> - id
> - name
> - email 
> - subject
> - message
> - url_path_file_upload
> - create_at
> - create_by
> - update_at
> - update_by

## Table :: contact_us
> - id
> - name
> - email 
> - subject
> - message
> - url_path_file_upload
> - create_at
> - create_by
> - update_at
> - update_by


## Table :: majalah
> - id
> - title
> - kategori
> - version_volume
> - version_number
> - edition
> - release_date
> - url_path_file
> - create_at
> - create_by
> - update_at
> - update_by

## Table :: reformasi_birokrasi
> - id
> - title
> - sub_page
> - kategori
> - release_date
> - url_path_file
> - create_at
> - create_by
> - update_at
> - update_by

## Table :: regulasi
> - id
> - title
> - sub_page
> - kategori
> - release_date
> - url_path_file
> - create_at
> - create_by
> - update_at
> - update_by

## Table :: data
> - id
> - title
> - sub_page
> - kategori
> - release_date
> - url_path_file
> - create_at
> - create_by
> - update_at
> - update_by

## Table :: organization_level
> - id
> - parent_id
> - name
> - position
> - status
> - create_at
> - create_by
> - update_at
> - update_by


## Table :: ms_category
> - code
> - name
> - group
> - remark
> - create_at
> - create_by
> - update_at
> - update_by


## Table :: ms_sub_page
> - code
> - name
> - group
> - remark
> - create_at
> - create_by
> - update_at
> - update_by


