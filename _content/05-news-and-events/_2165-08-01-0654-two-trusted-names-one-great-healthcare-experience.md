---
_license_key: aecacbba-ec9a-41c1-84f0-2fdf7b89c1e5
_language: en
_site_name: St. Paul Radiology
_content_root: _content
_site_url: http://www.stpaulradiology.com
_theme: spr
_entry_timestamps: true
_date_format: F jS, Y
_time_format: g:ia
_timezone: America/New_York
_taxonomy:
  - category
  - tags
  - practice_area
  - filter_letter
  - custom_nav
_taxonomy_slugify: true
_taxonomy_case_sensitive: false
_taxonomy_force_lowercase: false
_content_type: markdown
_enable_smartypants: true
_theme_cache_bust: false
_transform_destination: assets/img/resized
_transform_quality: 100
_allow_php: false
_yaml_mode: loose
_markdown_parser: standard
_parse_order:
  - content
  - tags
_fix_out_of_range_pagination: true
_http_cache_expires: false
_disable_member_cache: false
_enable_list_helpers: true
_environments:
  dev:
    - 'http://localhost*'
    - http://www.stpaulradiology.com/
    - '*.dev'
    - '*.localip'
    - '*.holmesmillet.com'
  live:
    - http://www.stpaulradiology.com/
_log_enabled: false
_log_level: error
_log_file_path: _logs
_log_file_prefix: site
_display_debug_panel: false
_admin_enabled: true
_admin_path: admin
_admin_theme: ascent
_admin_nav:
  dashboard: false
  pages: true
  members: true
  account: true
  system: true
  logs: true
  help: true
  view_site: true
  logout: true
  globals: true
  raven: true
_admin_start_page: pages
_enable_add_top_level_page: true
_enable_add_child_page: true
_enable_delete_page: true
_prepend_site_root_to_uploads: false
_allow_file_field_deletions: false
_disable_google_fonts: false
_cookies.lifetime: 1 day
_cookies.cipher: MCRYPT_RIJNDAEL_256
_cookies.cipher_mode: MCRYPT_MODE_CBC
_custom_transliteration: ""
_mode: 755
_public_path: ""
_site_root: /
_enable_static_pipeline: false
_routes:
  routes:
    /news-and-events/from/*: entries/archive
    /our-team/practice-area/*: team/filter
    /our-team/filter-letter/*: team/filter
  ignore: ""
_vanity_urls: ""
dashboard_main_content: "<h1>Replace this if you want to customize your dashboard's content</h1> <p>Hello wilderness.</p>"
dashboard_sidebar_content: '<h2>Useful Links</h2> <ul> <li><a href="http://statamic.com">Statamic.com</a></li> <li><a href="http://twitter.com/statamic">Statamic on Twitter</a></li> <li><a href="http://facebook.com/statamic">Statamic on Facebook</a></li> </ul> <a href="http://statamic.tenderapp.com" class="btn full-width">Get Statamic Support</a>'
_mimes:
  hqx: application/mac-binhex40
  cpt: application/mac-compactpro
  csv:
    - text/x-comma-separated-values
    - text/comma-separated-values
    - application/octet-stream
  bin: application/macbinary
  dms: application/octet-stream
  lha: application/octet-stream
  lzh: application/octet-stream
  exe:
    - application/octet-stream
    - application/x-msdownload
  class: application/octet-stream
  psd: application/x-photoshop
  so: application/octet-stream
  sea: application/octet-stream
  dll: application/octet-stream
  oda: application/oda
  pdf:
    - application/pdf
    - application/x-download
  ai: application/postscript
  eps: application/postscript
  ps: application/postscript
  smi: application/smil
  smil: application/smil
  mif: application/vnd.mif
  xls:
    - application/excel
    - application/vnd.ms-excel
    - application/msexcel
  ppt:
    - application/powerpoint
    - application/vnd.ms-powerpoint
  wbxml: application/wbxml
  wmlc: application/wmlc
  dcr: application/x-director
  dir: application/x-director
  dxr: application/x-director
  dvi: application/x-dvi
  gtar: application/x-gtar
  gz: application/x-gzip
  php:
    - application/x-httpd-php
    - text/x-php
  php4: application/x-httpd-php
  php3: application/x-httpd-php
  phtml: application/x-httpd-php
  phps: application/x-httpd-php-source
  js: application/x-javascript
  swf: application/x-shockwave-flash
  sit: application/x-stuffit
  tar: application/x-tar
  tgz:
    - application/x-tar
    - application/x-gzip-compressed
  xhtml: application/xhtml+xml
  xht: application/xhtml+xml
  zip:
    - application/x-zip
    - application/zip
    - application/x-zip-compressed
  mid: audio/midi
  midi: audio/midi
  mpga: audio/mpeg
  mp2: audio/mpeg
  mp3:
    - audio/mpeg
    - audio/mpg
    - audio/mpeg3
    - audio/mp3
  m4a: video/mp4
  m4v: video/x-f4v
  aif: audio/x-aiff
  aiff: audio/x-aiff
  aifc: audio/x-aiff
  ram: audio/x-pn-realaudio
  rm: audio/x-pn-realaudio
  rpm: audio/x-pn-realaudio-plugin
  ra: audio/x-realaudio
  rv: video/vnd.rn-realvideo
  wav: audio/x-wav
  bmp: image/bmp
  gif: image/gif
  jpeg:
    - image/jpeg
    - image/pjpeg
  jpg:
    - image/jpeg
    - image/pjpeg
  jpe:
    - image/jpeg
    - image/pjpeg
  png: image/png
  tiff: image/tiff
  tif: image/tiff
  css: text/css
  html: text/html
  htm: text/html
  shtml: text/html
  txt: text/plain
  text: text/plain
  log:
    - text/plain
    - text/x-log
  rtx: text/richtext
  rtf: text/rtf
  xml: text/xml
  xsl: text/xml
  mpeg: video/mpeg
  mpg: video/mpeg
  mpe: video/mpeg
  qt: video/quicktime
  mov: video/quicktime
  avi: video/x-msvideo
  movie: video/x-sgi-movie
  doc: application/msword
  docx: application/vnd.openxmlformats-officedocument.wordprocessingml.document
  xlsx: application/vnd.openxmlformats-officedocument.spreadsheetml.sheet
  word:
    - application/msword
    - application/octet-stream
  xl: application/excel
  eml: message/rfc822
  json:
    - application/json
    - text/json
  svg: image/svg+xml
_translations:
  en:
    translations:
      raven: Raven
      raven_forms: Raven Forms
      nav_title_raven: Forms
      nav_icon_raven: form
      export_csv: Export to CSV
      form: Form
      submissions: Submissions
      delete_files: Delete Files
      spam: Spam
      ham: Ham
      all_submissions: All Submissions
      mark_as_spam: Mark as Spam
      mark_as_ham: Mark as Ham
      batch_delete: Files deleted
      batch_spam: Moved to spam
      batch_ham: Moved to ham
      confirm_action: "Yes I'm Sure"
      nav_title_globals: Globals
      nav_icon_globals: globe
      editing_globals: Editing Globals
      add: Add
      delete: Delete
      list: List
      none: None
      view: View
      in: in
      remove: Remove
      cancel: Cancel
      move: Move
      toggle: Toggle
      today: today
      tomorrow: tomorrow
      yesterday: yesterday
      at: at
      home: Home
      dashboard: Dashboard
      pages: Pages
      content: Content
      members: Members
      account: Account
      system: System
      help: Help
      view_site: View Site
      logout: Log out
      logs: Logs
      entry: Entry
      entries: Entries
      create: Create
      new_entry: New Entry
      editing_entry: Editing entry
      create_entry: Create Entry
      delete_entry: Delete Entry
      view_entry: View Entry
      list_entries: List Entries
      take_action: Take Action
      delete_entries: Delete Entries
      confirm_delete: "Yes I'm Sure"
      page: Page
      edit_page: Edit Page
      editing_page: Editing Page
      new_top_level_page: New Top Level Page
      site_pages: Site Pages
      new_child_page: New Child Page
      view_page: View Page
      delete_page: Delete Page
      select_new_page_type: Select New Page Type
      parent: Parent
      or: or
      and: and
      pagedelete_confirm: Are you sure you wish to delete this page?
      update_available: update available
      up_to_date: up to date
      offline: The control panel is currently offline.
      title: Title
      slug: Slug
      date: Date
      number: Number
      editing: Editing
      enter_title: Enter a title...
      order_number: Order Number
      publish_date: Publish Date
      publish_time: Publish Time
      save: Save
      save_publish: Publish
      save_publish_continue: 'Publish & Continue'
      new: New
      status: Status
      live: Live
      draft: Draft
      hidden: Hidden
      login: Log in
      admin: Admin
      email: Email
      username: Username
      password: Password
      password_confirmation: Password Confirmation
      change_password: Change Password
      type_again: Type it again, please
      encrypt_password: Encrypt Password?
      first_name: First Name
      last_name: Last Name
      biography: Biography
      role: Role
      member: Member
      new_member: New Member
      creating_member: Creating new member
      editing_member: 'Editing member: '
      reset_password_url_invalid: This URL is invalid
      reset_password_url_expired: This link has expired
      member_doesnt_exist: "Member doesn't exist"
      site_logs: Site Logs
      clear_logs: Clear all logs
      log_file: Your log file
      log_unwritable: is not writable, and thus, logs cannot be written.
      showing: Showing
      messages_all: all messages
      messages_debug: only debug messages
      messages_info: only info messages
      messages_warn: only warn messages
      messages_error: only error messages
      messages_fatal: only fatal messages
      info_plus: info messages or worse
      warn_plus: warn messages or worse
      error_plus: error messages or worse
      messages_happened: that happened on
      messages_level: Level
      messages_when: When
      messages_what: What Caused This
      messages_page: Page
      messages_message: Message
      log_filter_nomessages: This log file exists, but contains no messages with this filter.
      log_nomessages: This log file exists, but there are no messages.
      log_nomessages_logged: No messages have been logged yet.
      logging_yes: 'This site <strong>is</strong> logging messages.'
      logging_no: 'This site <strong>is not</strong> logging messages.'
      log_messages: 'Messages are from the following level or worse: '
      log_turning_on: 'To turn on logging, set <code>_log_enabled</code> to <code>true</code> in <code>_config/settings.yaml</code>.'
      export_to_html: Export to HTML
      static_site_generator: Static Site Generator
      generated_files: Generated Files
      generate_html: Generate HTML Files
      download_site: Download Site
      site_unlicensed: This site is unlicensed. Please purchase and enter your license key.
      admin_404: That page did not exist, so we sent you here instead.
      already_exists: already exists
      is_required: is required
      content_not_found: Content not found!
      content_not_writable: "Whoops, your content folder and/or files aren't writable. You'll want to fix that."
      users_not_writable: "Whoops, your users folder and/or files aren't writable. You'll want to fix that."
      msg_password_encrypted: Password has been encrypted. Please login again.
      password_confirmation_required: and confirmation is required
      password_confirmation_match: and confirmation do not match
      password_confirmation_does_not_match: Password and password confirmation do not match.
      incorrect_username: Username not found
      incorrect_password: Incorrect password
      incorrect_username_password: Incorrect username or password. Try again.
      entry_deleted: Entry successfully deleted!
      entries_deleted: Entries successfully deleted!
      page_deleted: Page successfully deleted!
      page_unable_delete: Unable to delete page.
      member_deleted: Member successfully deleted!
      page_saved: Page saved successfully!
      entry_saved: Entry saved successfully!
      member_saved: Member saved successfully!
      invalid_username: The username entered contains invalid characters.
      username_already_exists: Someone with that username already exists.
      viewing_all: Viewing all
      error: Error
      error_form_submission: Sorry, an error prevented the form submission.
      are_you_sure: Are you sure? This cannot be undone.
      access_denied: Access Denied
      enable_curl: cURL must be enabled to perform a security test.
      upload_error_ini_size: File upload failed. The file’s size is more than PHP’s configuration allows.
      upload_error_form_size: File upload failed. The file’s size is more than the `MAX_FILE_SIZE` on the form allows.
      upload_error_err_partial: File upload failed. The file was only partially uploaded.
      upload_error_no_file: File upload failed. No file was chosen for upload.
      upload_error_no_temp_dir: File upload failed. No temporary directory has been specified.
      upload_error_cant_write: File upload failed. The temporary upload directory may not be writable.
      upload_error_extension: File upload failed. A PHP extension has stopped the file upload from working.
      upload_error_unknown: File upload failed for unknown reasons.
      security_status: Security Status
      security_files_security_check: Site Files Security Check
      secure_status: Secure Status
      password_status: Password Status
      curl_needed: "You'll need to enable cURL on your server to automatically test your security."
      folder_file: Folder/File
      action_required: Action Required
      secure: Secure
      unsecure: Unsecure
      user_accounts_security_check: User Accounts Security Check
      user_file: User File
      encrypted: Encrypted
      unencrypted: Unencrypted
      action_encrypt_password: Encrypt Password
      security_app_folder: "Your application folder is accessible to the web. While not critical, it's best practice to protect this folder."
      security_config_folder: Your config folder is accessible to the web. It is critical that you protect this folder.
      security_settings_files: Your settings files are accessible to the web. It is critical that you protect these files.
      security_user_files: Your user files are accessible to the web. It is critical that you protect these files.
      security_content_folder: Your content folder is accessible to the web. While not critical, it is best practice to protect this folder.
      security_template_files: Your theme template files are accessible to the web. While not critical, it is best practice to protect these files.
      security_logs_folder: Your logs folder is accessible to the web. It is critical that you protect this folder.
      location_name: Name of Location
      latitude: Latitude
      longitude: Longitude
      view_page_history: View Revisions
      choose_revision_to_view: Choose a revision to view
      view_this_revision: View this revision
      first_save: First saved revision
      published_on: Published on
      you_are_here: You Are Here
      viewing_revision: You are viewing a revision of this page from %s. You can re-publish it as-is, make changes then publish, or
      viewing_revision_link: go back to the live version
      what_changed: Describe What Changed
      file_deleted: File deleted
      file_renamed: File renamed
      upload_file: Upload a file
      drop_your_file: Drop your file
      max_files_reached: Max files reached
      choose_existing_file: Choose an existing file
      choose_file_from: Choose a file from
      file_doesnt_exist: File does not exist
      file_no_config: No config provided
      file_no_path: No path provided
      file_deleting_not_permitted: Deleting files is not permitted
      hide_all: Hide all
      show_all: Show all
      options: Options
      by: by
      published: Published
cookies.lifetime: 1 day
_cookies.secret_key: "T%?QR?me=t8oT>+,vMlf5nN;CQ?dau7Dw.>*@st%%Yv(.dJ`vBb,.wz~,t(SrnH21#f#gqcUq6U]hW|_2F[}}~3Sg)sC[a2Y8,CV(bMgW15NFl'6jfc6b1]dGO8ACOtO"
theme_path: /admin/themes/ascent/
templates.path: ./admin/themes/ascent/
whoops.editor: sublime
logged_in: true
username: Tam
is_admin: true
current_member:
  logged_in: true
  username: Tam
  email: tam@holmesmillet.com
  first_name: Tam
  last_name: Pham
  password: ""
  password_hash: $2a$08$uz1bQM1uHuP.EcqPcdSt5e1qhufljre9Zzzce8IKUjFMCrDVRsSP2
  roles:
    - member
    - admin
  _uid: FQFwdV570278a385155D2F4cVf5
  biography_raw: ""
  biography: ""
  is_member: 'true'
  is_admin: 'true'
get:
  path: /05-news-and-events/__2019-08-01-0654-two-trusted-names-one-great-healthcare-experience
post:
  page:
    yaml:
      status: hidden
      title: Two trusted names. One great healthcare experience.
      img_primary: '[&quot;/[]&quot;]'
      category: News
      tags:
        - news
      content: ""
    full_slug: /05-news-and-events/two-trusted-names-one-great-healthcare-experience
    type: date
    folder: /05-news-and-events
    original_slug: two-trusted-names-one-great-healthcare-experience
    original_datestamp: 2019-08-01
    original_timestamp: "0654"
    original_numeric: ""
    fieldset: news_and_events
    meta:
      slug: two-trusted-names-one-great-healthcare-experience
      publish-date: 2210-12-01
      publish-time: 06:54 AM
  return: ""
  hour: "06"
  minute: "54"
  meridian: AM
get_post:
  path: /05-news-and-events/__2019-08-01-0654-two-trusted-names-one-great-healthcare-experience
  page:
    yaml:
      status: hidden
      title: Two trusted names. One great healthcare experience.
      img_primary: '[&quot;/[]&quot;]'
      category: News
      tags:
        - news
      content: ""
    full_slug: /05-news-and-events/two-trusted-names-one-great-healthcare-experience
    type: date
    folder: /05-news-and-events
    original_slug: two-trusted-names-one-great-healthcare-experience
    original_datestamp: 2019-08-01
    original_timestamp: "0654"
    original_numeric: ""
    fieldset: news_and_events
    meta:
      slug: two-trusted-names-one-great-healthcare-experience
      publish-date: 2210-12-01
      publish-time: 06:54 AM
  return: ""
  hour: "06"
  minute: "54"
  meridian: AM
homepage: /
now: 1475782371
latest_version_url: ""
latest_version: ""
title: Two trusted names. One great healthcare experience.
img_primary: '/[]'
category: News
tags:
  - news
---
