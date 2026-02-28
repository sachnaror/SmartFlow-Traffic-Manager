├── SmartFlow-Traffic-Manager/
│   ├── LICENSE
│   ├── requirements.txt
│   ├── yolov8n.pt
│   ├── test_accident_detector.py
│   ├── test_accident_img.py
│   ├── test_traffic_data.py
│   ├── README.md
│   ├── test_monitoring.py
│   ├── instance/
│   │   └── sftm.sqlite
│   ├── sftm_server/
│   │   ├── db.py
│   │   ├── schema.sql
│   │   ├── static/
│   │   │   ├── images/
│   │   │   │   ├── temp.jpg
│   │   │   │   └── hero-img.png
│   │   │   ├── js/
│   │   │   │   └── main.js
│   │   │   ├── style/
│   │   │   │   └── style.css
│   │   │   ├── vendor/
│   │   │   │   ├── tinymce/
│   │   │   │   │   ├── license.md
│   │   │   │   │   ├── tinymce.d.ts
│   │   │   │   │   ├── CHANGELOG.md
│   │   │   │   │   ├── bower.json
│   │   │   │   │   ├── README.md
│   │   │   │   │   ├── tinymce.js
│   │   │   │   │   ├── package.json
│   │   │   │   │   ├── tinymce.min.js
│   │   │   │   │   └── composer.json
│   │   │   │   │   ├── plugins/
│   │   │   │   │   │   ├── visualblocks/
│   │   │   │   │   │   │   ├── index.js
│   │   │   │   │   │   │   ├── plugin.min.js
│   │   │   │   │   │   │   └── plugin.js
│   │   │   │   │   │   ├── directionality/
│   │   │   │   │   │   │   ├── index.js
│   │   │   │   │   │   │   ├── plugin.min.js
│   │   │   │   │   │   │   └── plugin.js
│   │   │   │   │   │   ├── wordcount/
│   │   │   │   │   │   │   ├── index.js
│   │   │   │   │   │   │   ├── plugin.min.js
│   │   │   │   │   │   │   └── plugin.js
│   │   │   │   │   │   ├── lists/
│   │   │   │   │   │   │   ├── index.js
│   │   │   │   │   │   │   ├── plugin.min.js
│   │   │   │   │   │   │   └── plugin.js
│   │   │   │   │   │   ├── accordion/
│   │   │   │   │   │   │   ├── index.js
│   │   │   │   │   │   │   ├── plugin.min.js
│   │   │   │   │   │   │   └── plugin.js
│   │   │   │   │   │   ├── quickbars/
│   │   │   │   │   │   │   ├── index.js
│   │   │   │   │   │   │   ├── plugin.min.js
│   │   │   │   │   │   │   └── plugin.js
│   │   │   │   │   │   ├── codesample/
│   │   │   │   │   │   │   ├── index.js
│   │   │   │   │   │   │   ├── plugin.min.js
│   │   │   │   │   │   │   └── plugin.js
│   │   │   │   │   │   ├── importcss/
│   │   │   │   │   │   │   ├── index.js
│   │   │   │   │   │   │   ├── plugin.min.js
│   │   │   │   │   │   │   └── plugin.js
│   │   │   │   │   │   ├── code/
│   │   │   │   │   │   │   ├── index.js
│   │   │   │   │   │   │   ├── plugin.min.js
│   │   │   │   │   │   │   └── plugin.js
│   │   │   │   │   │   ├── searchreplace/
│   │   │   │   │   │   │   ├── index.js
│   │   │   │   │   │   │   ├── plugin.min.js
│   │   │   │   │   │   │   └── plugin.js
│   │   │   │   │   │   ├── nonbreaking/
│   │   │   │   │   │   │   ├── index.js
│   │   │   │   │   │   │   ├── plugin.min.js
│   │   │   │   │   │   │   └── plugin.js
│   │   │   │   │   │   ├── image/
│   │   │   │   │   │   │   ├── index.js
│   │   │   │   │   │   │   ├── plugin.min.js
│   │   │   │   │   │   │   └── plugin.js
│   │   │   │   │   │   ├── autoresize/
│   │   │   │   │   │   │   ├── index.js
│   │   │   │   │   │   │   ├── plugin.min.js
│   │   │   │   │   │   │   └── plugin.js
│   │   │   │   │   │   ├── autosave/
│   │   │   │   │   │   │   ├── index.js
│   │   │   │   │   │   │   ├── plugin.min.js
│   │   │   │   │   │   │   └── plugin.js
│   │   │   │   │   │   ├── insertdatetime/
│   │   │   │   │   │   │   ├── index.js
│   │   │   │   │   │   │   ├── plugin.min.js
│   │   │   │   │   │   │   └── plugin.js
│   │   │   │   │   │   ├── link/
│   │   │   │   │   │   │   ├── index.js
│   │   │   │   │   │   │   ├── plugin.min.js
│   │   │   │   │   │   │   └── plugin.js
│   │   │   │   │   │   ├── table/
│   │   │   │   │   │   │   ├── index.js
│   │   │   │   │   │   │   ├── plugin.min.js
│   │   │   │   │   │   │   └── plugin.js
│   │   │   │   │   │   ├── charmap/
│   │   │   │   │   │   │   ├── index.js
│   │   │   │   │   │   │   ├── plugin.min.js
│   │   │   │   │   │   │   └── plugin.js
│   │   │   │   │   │   ├── advlist/
│   │   │   │   │   │   │   ├── index.js
│   │   │   │   │   │   │   ├── plugin.min.js
│   │   │   │   │   │   │   └── plugin.js
│   │   │   │   │   │   ├── preview/
│   │   │   │   │   │   │   ├── index.js
│   │   │   │   │   │   │   ├── plugin.min.js
│   │   │   │   │   │   │   └── plugin.js
│   │   │   │   │   │   ├── anchor/
│   │   │   │   │   │   │   ├── index.js
│   │   │   │   │   │   │   ├── plugin.min.js
│   │   │   │   │   │   │   └── plugin.js
│   │   │   │   │   │   ├── autolink/
│   │   │   │   │   │   │   ├── index.js
│   │   │   │   │   │   │   ├── plugin.min.js
│   │   │   │   │   │   │   └── plugin.js
│   │   │   │   │   │   ├── pagebreak/
│   │   │   │   │   │   │   ├── index.js
│   │   │   │   │   │   │   ├── plugin.min.js
│   │   │   │   │   │   │   └── plugin.js
│   │   │   │   │   │   ├── fullscreen/
│   │   │   │   │   │   │   ├── index.js
│   │   │   │   │   │   │   ├── plugin.min.js
│   │   │   │   │   │   │   └── plugin.js
│   │   │   │   │   │   ├── visualchars/
│   │   │   │   │   │   │   ├── index.js
│   │   │   │   │   │   │   ├── plugin.min.js
│   │   │   │   │   │   │   └── plugin.js
│   │   │   │   │   │   ├── save/
│   │   │   │   │   │   │   ├── index.js
│   │   │   │   │   │   │   ├── plugin.min.js
│   │   │   │   │   │   │   └── plugin.js
│   │   │   │   │   │   ├── emoticons/
│   │   │   │   │   │   │   ├── index.js
│   │   │   │   │   │   │   ├── plugin.min.js
│   │   │   │   │   │   │   └── plugin.js
│   │   │   │   │   │   │   ├── js/
│   │   │   │   │   │   │   │   ├── emojis.min.js
│   │   │   │   │   │   │   │   ├── emojis.js
│   │   │   │   │   │   │   │   ├── emojiimages.min.js
│   │   │   │   │   │   │   │   └── emojiimages.js
│   │   │   │   │   │   ├── help/
│   │   │   │   │   │   │   ├── index.js
│   │   │   │   │   │   │   ├── plugin.min.js
│   │   │   │   │   │   │   └── plugin.js
│   │   │   │   │   │   │   ├── js/
│   │   │   │   │   │   │   │   ├── i18n/
│   │   │   │   │   │   │   │   │   ├── keynav/
│   │   │   │   │   │   │   │   │   │   ├── sv_SE.js
│   │   │   │   │   │   │   │   │   │   ├── pt_PT.js
│   │   │   │   │   │   │   │   │   │   ├── vi.js
│   │   │   │   │   │   │   │   │   │   ├── kk.js
│   │   │   │   │   │   │   │   │   │   ├── pl.js
│   │   │   │   │   │   │   │   │   │   ├── el.js
│   │   │   │   │   │   │   │   │   │   ├── hr.js
│   │   │   │   │   │   │   │   │   │   ├── ms.js
│   │   │   │   │   │   │   │   │   │   ├── fi.js
│   │   │   │   │   │   │   │   │   │   ├── ru.js
│   │   │   │   │   │   │   │   │   │   ├── eu.js
│   │   │   │   │   │   │   │   │   │   ├── th_TH.js
│   │   │   │   │   │   │   │   │   │   ├── he_IL.js
│   │   │   │   │   │   │   │   │   │   ├── ja.js
│   │   │   │   │   │   │   │   │   │   ├── id.js
│   │   │   │   │   │   │   │   │   │   ├── hu_HU.js
│   │   │   │   │   │   │   │   │   │   ├── ca.js
│   │   │   │   │   │   │   │   │   │   ├── ko_KR.js
│   │   │   │   │   │   │   │   │   │   ├── da.js
│   │   │   │   │   │   │   │   │   │   ├── fa.js
│   │   │   │   │   │   │   │   │   │   ├── de.js
│   │   │   │   │   │   │   │   │   │   ├── en.js
│   │   │   │   │   │   │   │   │   │   ├── zh_CN.js
│   │   │   │   │   │   │   │   │   │   ├── hi.js
│   │   │   │   │   │   │   │   │   │   ├── uk.js
│   │   │   │   │   │   │   │   │   │   ├── cs.js
│   │   │   │   │   │   │   │   │   │   ├── nl.js
│   │   │   │   │   │   │   │   │   │   ├── sl_SI.js
│   │   │   │   │   │   │   │   │   │   ├── bg_BG.js
│   │   │   │   │   │   │   │   │   │   ├── nb_NO.js
│   │   │   │   │   │   │   │   │   │   ├── fr_FR.js
│   │   │   │   │   │   │   │   │   │   ├── ar.js
│   │   │   │   │   │   │   │   │   │   ├── sk.js
│   │   │   │   │   │   │   │   │   │   ├── it.js
│   │   │   │   │   │   │   │   │   │   ├── es.js
│   │   │   │   │   │   │   │   │   │   ├── ro.js
│   │   │   │   │   │   │   │   │   │   ├── zh_TW.js
│   │   │   │   │   │   │   │   │   │   ├── pt_BR.js
│   │   │   │   │   │   │   │   │   │   └── tr.js
│   │   │   │   │   │   ├── media/
│   │   │   │   │   │   │   ├── index.js
│   │   │   │   │   │   │   ├── plugin.min.js
│   │   │   │   │   │   │   └── plugin.js
│   │   │   │   │   ├── skins/
│   │   │   │   │   │   ├── ui/
│   │   │   │   │   │   │   ├── oxide/
│   │   │   │   │   │   │   │   ├── skin.shadowdom.js
│   │   │   │   │   │   │   │   ├── content.inline.js
│   │   │   │   │   │   │   │   ├── content.css
│   │   │   │   │   │   │   │   ├── skin.min.css
│   │   │   │   │   │   │   │   ├── content.inline.min.css
│   │   │   │   │   │   │   │   ├── skin.shadowdom.css
│   │   │   │   │   │   │   │   ├── skin.js
│   │   │   │   │   │   │   │   ├── skin.shadowdom.min.css
│   │   │   │   │   │   │   │   ├── content.js
│   │   │   │   │   │   │   │   ├── content.min.css
│   │   │   │   │   │   │   │   ├── content.inline.css
│   │   │   │   │   │   │   │   └── skin.css
│   │   │   │   │   │   │   ├── tinymce-5/
│   │   │   │   │   │   │   │   ├── skin.shadowdom.js
│   │   │   │   │   │   │   │   ├── content.inline.js
│   │   │   │   │   │   │   │   ├── content.css
│   │   │   │   │   │   │   │   ├── skin.min.css
│   │   │   │   │   │   │   │   ├── content.inline.min.css
│   │   │   │   │   │   │   │   ├── skin.shadowdom.css
│   │   │   │   │   │   │   │   ├── skin.js
│   │   │   │   │   │   │   │   ├── skin.shadowdom.min.css
│   │   │   │   │   │   │   │   ├── content.js
│   │   │   │   │   │   │   │   ├── content.min.css
│   │   │   │   │   │   │   │   ├── content.inline.css
│   │   │   │   │   │   │   │   └── skin.css
│   │   │   │   │   │   │   ├── tinymce-5-dark/
│   │   │   │   │   │   │   │   ├── skin.shadowdom.js
│   │   │   │   │   │   │   │   ├── content.inline.js
│   │   │   │   │   │   │   │   ├── content.css
│   │   │   │   │   │   │   │   ├── skin.min.css
│   │   │   │   │   │   │   │   ├── content.inline.min.css
│   │   │   │   │   │   │   │   ├── skin.shadowdom.css
│   │   │   │   │   │   │   │   ├── skin.js
│   │   │   │   │   │   │   │   ├── skin.shadowdom.min.css
│   │   │   │   │   │   │   │   ├── content.js
│   │   │   │   │   │   │   │   ├── content.min.css
│   │   │   │   │   │   │   │   ├── content.inline.css
│   │   │   │   │   │   │   │   └── skin.css
│   │   │   │   │   │   │   ├── oxide-dark/
│   │   │   │   │   │   │   │   ├── skin.shadowdom.js
│   │   │   │   │   │   │   │   ├── content.inline.js
│   │   │   │   │   │   │   │   ├── content.css
│   │   │   │   │   │   │   │   ├── skin.min.css
│   │   │   │   │   │   │   │   ├── content.inline.min.css
│   │   │   │   │   │   │   │   ├── skin.shadowdom.css
│   │   │   │   │   │   │   │   ├── skin.js
│   │   │   │   │   │   │   │   ├── skin.shadowdom.min.css
│   │   │   │   │   │   │   │   ├── content.js
│   │   │   │   │   │   │   │   ├── content.min.css
│   │   │   │   │   │   │   │   ├── content.inline.css
│   │   │   │   │   │   │   │   └── skin.css
│   │   │   │   │   │   ├── content/
│   │   │   │   │   │   │   ├── default/
│   │   │   │   │   │   │   │   ├── content.css
│   │   │   │   │   │   │   │   ├── content.js
│   │   │   │   │   │   │   │   └── content.min.css
│   │   │   │   │   │   │   ├── document/
│   │   │   │   │   │   │   │   ├── content.css
│   │   │   │   │   │   │   │   ├── content.js
│   │   │   │   │   │   │   │   └── content.min.css
│   │   │   │   │   │   │   ├── writer/
│   │   │   │   │   │   │   │   ├── content.css
│   │   │   │   │   │   │   │   ├── content.js
│   │   │   │   │   │   │   │   └── content.min.css
│   │   │   │   │   │   │   ├── tinymce-5/
│   │   │   │   │   │   │   │   ├── content.css
│   │   │   │   │   │   │   │   ├── content.js
│   │   │   │   │   │   │   │   └── content.min.css
│   │   │   │   │   │   │   ├── tinymce-5-dark/
│   │   │   │   │   │   │   │   ├── content.css
│   │   │   │   │   │   │   │   ├── content.js
│   │   │   │   │   │   │   │   └── content.min.css
│   │   │   │   │   │   │   ├── dark/
│   │   │   │   │   │   │   │   ├── content.css
│   │   │   │   │   │   │   │   ├── content.js
│   │   │   │   │   │   │   │   └── content.min.css
│   │   │   │   │   ├── models/
│   │   │   │   │   │   ├── dom/
│   │   │   │   │   │   │   ├── model.min.js
│   │   │   │   │   │   │   ├── index.js
│   │   │   │   │   │   │   └── model.js
│   │   │   │   │   ├── icons/
│   │   │   │   │   │   ├── default/
│   │   │   │   │   │   │   ├── icons.js
│   │   │   │   │   │   │   ├── icons.min.js
│   │   │   │   │   │   │   └── index.js
│   │   │   │   │   ├── themes/
│   │   │   │   │   │   ├── silver/
│   │   │   │   │   │   │   ├── index.js
│   │   │   │   │   │   │   ├── theme.js
│   │   │   │   │   │   │   └── theme.min.js
│   │   │   │   ├── swiper/
│   │   │   │   │   ├── swiper-bundle.min.css
│   │   │   │   │   ├── swiper-bundle.min.js
│   │   │   │   │   └── swiper-bundle.min.js.map
│   │   │   │   ├── isotope-layout/
│   │   │   │   │   ├── isotope.pkgd.min.js
│   │   │   │   │   └── isotope.pkgd.js
│   │   │   │   ├── bootstrap/
│   │   │   │   │   ├── css/
│   │   │   │   │   │   ├── bootstrap.min.css
│   │   │   │   │   │   ├── bootstrap-grid.rtl.min.css
│   │   │   │   │   │   ├── bootstrap-utilities.rtl.css
│   │   │   │   │   │   ├── bootstrap-grid.rtl.min.css.map
│   │   │   │   │   │   ├── bootstrap.rtl.min.css.map
│   │   │   │   │   │   ├── bootstrap.rtl.css.map
│   │   │   │   │   │   ├── bootstrap-reboot.rtl.css
│   │   │   │   │   │   ├── bootstrap-reboot.min.css.map
│   │   │   │   │   │   ├── bootstrap-utilities.css
│   │   │   │   │   │   ├── bootstrap-reboot.rtl.min.css.map
│   │   │   │   │   │   ├── bootstrap.css
│   │   │   │   │   │   ├── bootstrap-utilities.min.css.map
│   │   │   │   │   │   ├── bootstrap-grid.css.map
│   │   │   │   │   │   ├── bootstrap-grid.min.css
│   │   │   │   │   │   ├── bootstrap.rtl.min.css
│   │   │   │   │   │   ├── bootstrap.css.map
│   │   │   │   │   │   ├── bootstrap-grid.rtl.css.map
│   │   │   │   │   │   ├── bootstrap.min.css.map
│   │   │   │   │   │   ├── bootstrap-reboot.min.css
│   │   │   │   │   │   ├── bootstrap-utilities.rtl.min.css.map
│   │   │   │   │   │   ├── bootstrap.rtl.css
│   │   │   │   │   │   ├── bootstrap-utilities.rtl.css.map
│   │   │   │   │   │   ├── bootstrap-reboot.rtl.css.map
│   │   │   │   │   │   ├── bootstrap-reboot.css
│   │   │   │   │   │   ├── bootstrap-utilities.min.css
│   │   │   │   │   │   ├── bootstrap-grid.css
│   │   │   │   │   │   ├── bootstrap-utilities.css.map
│   │   │   │   │   │   ├── bootstrap-utilities.rtl.min.css
│   │   │   │   │   │   ├── bootstrap-reboot.rtl.min.css
│   │   │   │   │   │   ├── bootstrap-grid.min.css.map
│   │   │   │   │   │   ├── bootstrap-grid.rtl.css
│   │   │   │   │   │   └── bootstrap-reboot.css.map
│   │   │   │   │   ├── js/
│   │   │   │   │   │   ├── bootstrap.esm.min.js
│   │   │   │   │   │   ├── bootstrap.esm.js
│   │   │   │   │   │   ├── bootstrap.bundle.js
│   │   │   │   │   │   ├── bootstrap.bundle.min.js.map
│   │   │   │   │   │   ├── bootstrap.bundle.js.map
│   │   │   │   │   │   ├── bootstrap.esm.js.map
│   │   │   │   │   │   ├── bootstrap.js
│   │   │   │   │   │   ├── bootstrap.bundle.min.js
│   │   │   │   │   │   ├── bootstrap.min.js
│   │   │   │   │   │   ├── bootstrap.esm.min.js.map
│   │   │   │   │   │   ├── bootstrap.js.map
│   │   │   │   │   │   └── bootstrap.min.js.map
│   │   │   │   ├── chart.js/
│   │   │   │   │   ├── helpers.cjs.map
│   │   │   │   │   ├── index.umd.d.ts
│   │   │   │   │   ├── chart.js
│   │   │   │   │   ├── types.d.ts
│   │   │   │   │   ├── chart.umd.js
│   │   │   │   │   ├── chart.js.map
│   │   │   │   │   ├── helpers.cjs
│   │   │   │   │   ├── helpers.js.map
│   │   │   │   │   ├── chart.cjs.map
│   │   │   │   │   ├── helpers.js
│   │   │   │   │   ├── index.d.ts
│   │   │   │   │   ├── chart.cjs
│   │   │   │   │   └── chart.umd.js.map
│   │   │   │   │   ├── types/
│   │   │   │   │   │   ├── color.d.ts
│   │   │   │   │   │   ├── geometric.d.ts
│   │   │   │   │   │   ├── animation.d.ts
│   │   │   │   │   │   ├── utils.d.ts
│   │   │   │   │   │   ├── layout.d.ts
│   │   │   │   │   │   ├── index.d.ts
│   │   │   │   │   │   └── basic.d.ts
│   │   │   │   │   ├── core/
│   │   │   │   │   │   ├── core.plugins.d.ts
│   │   │   │   │   │   ├── core.config.d.ts
│   │   │   │   │   │   ├── core.typedRegistry.d.ts
│   │   │   │   │   │   ├── core.animator.d.ts
│   │   │   │   │   │   ├── core.element.d.ts
│   │   │   │   │   │   ├── core.defaults.d.ts
│   │   │   │   │   │   ├── core.registry.d.ts
│   │   │   │   │   │   ├── core.ticks.d.ts
│   │   │   │   │   │   ├── core.scale.defaults.d.ts
│   │   │   │   │   │   ├── core.layouts.d.ts
│   │   │   │   │   │   ├── core.controller.d.ts
│   │   │   │   │   │   ├── core.animations.d.ts
│   │   │   │   │   │   ├── core.animations.defaults.d.ts
│   │   │   │   │   │   ├── core.layouts.defaults.d.ts
│   │   │   │   │   │   ├── core.interaction.d.ts
│   │   │   │   │   │   ├── core.scale.d.ts
│   │   │   │   │   │   ├── core.animation.d.ts
│   │   │   │   │   │   ├── core.datasetController.d.ts
│   │   │   │   │   │   ├── index.d.ts
│   │   │   │   │   │   ├── core.scale.autoskip.d.ts
│   │   │   │   │   │   └── core.adapters.d.ts
│   │   │   │   │   ├── plugins/
│   │   │   │   │   │   ├── plugin.tooltip.d.ts
│   │   │   │   │   │   ├── plugin.title.d.ts
│   │   │   │   │   │   ├── plugin.colors.d.ts
│   │   │   │   │   │   ├── plugin.legend.d.ts
│   │   │   │   │   │   ├── plugin.subtitle.d.ts
│   │   │   │   │   │   ├── index.d.ts
│   │   │   │   │   │   └── plugin.decimation.d.ts
│   │   │   │   │   │   ├── plugin.filler/
│   │   │   │   │   │   │   ├── filler.target.d.ts
│   │   │   │   │   │   │   ├── filler.options.d.ts
│   │   │   │   │   │   │   ├── simpleArc.d.ts
│   │   │   │   │   │   │   ├── filler.drawing.d.ts
│   │   │   │   │   │   │   ├── filler.target.stack.d.ts
│   │   │   │   │   │   │   ├── index.d.ts
│   │   │   │   │   │   │   ├── filler.helper.d.ts
│   │   │   │   │   │   │   └── filler.segment.d.ts
│   │   │   │   │   ├── platform/
│   │   │   │   │   │   ├── platform.base.d.ts
│   │   │   │   │   │   ├── platform.basic.d.ts
│   │   │   │   │   │   ├── platform.dom.d.ts
│   │   │   │   │   │   └── index.d.ts
│   │   │   │   │   ├── scales/
│   │   │   │   │   │   ├── scale.timeseries.d.ts
│   │   │   │   │   │   ├── scale.linearbase.d.ts
│   │   │   │   │   │   ├── scale.logarithmic.d.ts
│   │   │   │   │   │   ├── scale.category.d.ts
│   │   │   │   │   │   ├── scale.radialLinear.d.ts
│   │   │   │   │   │   ├── scale.time.d.ts
│   │   │   │   │   │   ├── index.d.ts
│   │   │   │   │   │   └── scale.linear.d.ts
│   │   │   │   │   ├── chunks/
│   │   │   │   │   │   ├── helpers.segment.js
│   │   │   │   │   │   ├── helpers.segment.cjs
│   │   │   │   │   │   ├── helpers.segment.cjs.map
│   │   │   │   │   │   └── helpers.segment.js.map
│   │   │   │   │   ├── elements/
│   │   │   │   │   │   ├── element.line.d.ts
│   │   │   │   │   │   ├── element.bar.d.ts
│   │   │   │   │   │   ├── element.point.d.ts
│   │   │   │   │   │   ├── element.arc.d.ts
│   │   │   │   │   │   └── index.d.ts
│   │   │   │   │   ├── controllers/
│   │   │   │   │   │   ├── controller.radar.d.ts
│   │   │   │   │   │   ├── controller.bar.d.ts
│   │   │   │   │   │   ├── controller.bubble.d.ts
│   │   │   │   │   │   ├── controller.pie.d.ts
│   │   │   │   │   │   ├── controller.doughnut.d.ts
│   │   │   │   │   │   ├── index.d.ts
│   │   │   │   │   │   ├── controller.polarArea.d.ts
│   │   │   │   │   │   ├── controller.line.d.ts
│   │   │   │   │   │   └── controller.scatter.d.ts
│   │   │   │   │   ├── helpers/
│   │   │   │   │   │   ├── helpers.config.types.d.ts
│   │   │   │   │   │   ├── helpers.extras.d.ts
│   │   │   │   │   │   ├── helpers.dom.d.ts
│   │   │   │   │   │   ├── helpers.rtl.d.ts
│   │   │   │   │   │   ├── helpers.options.d.ts
│   │   │   │   │   │   ├── helpers.math.d.ts
│   │   │   │   │   │   ├── helpers.interpolation.d.ts
│   │   │   │   │   │   ├── helpers.canvas.d.ts
│   │   │   │   │   │   ├── helpers.color.d.ts
│   │   │   │   │   │   ├── helpers.intl.d.ts
│   │   │   │   │   │   ├── helpers.curve.d.ts
│   │   │   │   │   │   ├── helpers.collection.d.ts
│   │   │   │   │   │   ├── helpers.segment.d.ts
│   │   │   │   │   │   ├── helpers.easing.d.ts
│   │   │   │   │   │   ├── helpers.config.d.ts
│   │   │   │   │   │   ├── index.d.ts
│   │   │   │   │   │   └── helpers.core.d.ts
│   │   │   │   ├── glightbox/
│   │   │   │   │   ├── css/
│   │   │   │   │   │   ├── glightbox.css
│   │   │   │   │   │   └── glightbox.min.css
│   │   │   │   │   ├── js/
│   │   │   │   │   │   ├── glightbox.js
│   │   │   │   │   │   └── glightbox.min.js
│   │   │   │   ├── waypoints/
│   │   │   │   │   └── noframework.waypoints.js
│   │   │   │   ├── bootstrap-icons/
│   │   │   │   │   ├── bootstrap-icons.css
│   │   │   │   │   ├── bootstrap-icons.scss
│   │   │   │   │   ├── bootstrap-icons.min.css
│   │   │   │   │   └── bootstrap-icons.json
│   │   │   │   │   ├── fonts/
│   │   │   │   │   │   ├── bootstrap-icons.woff2
│   │   │   │   │   │   └── bootstrap-icons.woff
│   │   │   │   ├── remixicon/
│   │   │   │   │   ├── remixicon.woff2
│   │   │   │   │   ├── remixicon.css
│   │   │   │   │   ├── remixicon.less
│   │   │   │   │   ├── remixicon.svg
│   │   │   │   │   ├── remixicon.eot
│   │   │   │   │   ├── remixicon.symbol.svg
│   │   │   │   │   ├── remixicon.glyph.json
│   │   │   │   │   ├── remixicon.ttf
│   │   │   │   │   └── remixicon.woff
│   │   │   │   ├── php-email-form/
│   │   │   │   │   └── validate.js
│   │   │   │   ├── boxicons/
│   │   │   │   │   ├── css/
│   │   │   │   │   │   ├── animations.css
│   │   │   │   │   │   ├── boxicons.min.css
│   │   │   │   │   │   ├── transformations.css
│   │   │   │   │   │   └── boxicons.css
│   │   │   │   │   ├── fonts/
│   │   │   │   │   │   ├── boxicons.woff
│   │   │   │   │   │   ├── boxicons.ttf
│   │   │   │   │   │   ├── boxicons.eot
│   │   │   │   │   │   ├── boxicons.woff2
│   │   │   │   │   │   └── boxicons.svg
│   │   │   │   ├── simple-datatables/
│   │   │   │   │   ├── simple-datatables.js
│   │   │   │   │   └── style.css
│   │   │   │   ├── apexcharts/
│   │   │   │   │   ├── apexcharts.esm.js
│   │   │   │   │   ├── apexcharts.common.js
│   │   │   │   │   ├── apexcharts.css
│   │   │   │   │   ├── apexcharts.js
│   │   │   │   │   ├── apexcharts.min.js
│   │   │   │   │   └── apexcharts.amd.js
│   │   │   │   │   ├── locales/
│   │   │   │   │   │   ├── hy.json
│   │   │   │   │   │   ├── ua.json
│   │   │   │   │   │   ├── tr.json
│   │   │   │   │   │   ├── sl.json
│   │   │   │   │   │   ├── hu.json
│   │   │   │   │   │   ├── rs.json
│   │   │   │   │   │   ├── lt.json
│   │   │   │   │   │   ├── be-cyrl.json
│   │   │   │   │   │   ├── nl.json
│   │   │   │   │   │   ├── ms.json
│   │   │   │   │   │   ├── ja.json
│   │   │   │   │   │   ├── de.json
│   │   │   │   │   │   ├── ru.json
│   │   │   │   │   │   ├── pl.json
│   │   │   │   │   │   ├── be-latn.json
│   │   │   │   │   │   ├── fi.json
│   │   │   │   │   │   ├── zh-cn.json
│   │   │   │   │   │   ├── sk.json
│   │   │   │   │   │   ├── pt.json
│   │   │   │   │   │   ├── en.json
│   │   │   │   │   │   ├── ka.json
│   │   │   │   │   │   ├── it.json
│   │   │   │   │   │   ├── hr.json
│   │   │   │   │   │   ├── et.json
│   │   │   │   │   │   ├── sq.json
│   │   │   │   │   │   ├── fr.json
│   │   │   │   │   │   ├── el.json
│   │   │   │   │   │   ├── hi.json
│   │   │   │   │   │   ├── ca.json
│   │   │   │   │   │   ├── pt-br.json
│   │   │   │   │   │   ├── ko.json
│   │   │   │   │   │   ├── he.json
│   │   │   │   │   │   ├── se.json
│   │   │   │   │   │   ├── zh-tw.json
│   │   │   │   │   │   ├── fa.json
│   │   │   │   │   │   ├── cs.json
│   │   │   │   │   │   ├── id.json
│   │   │   │   │   │   ├── lv.json
│   │   │   │   │   │   ├── da.json
│   │   │   │   │   │   ├── th.json
│   │   │   │   │   │   ├── es.json
│   │   │   │   │   │   ├── ar.json
│   │   │   │   │   │   └── nb.json
│   │   │   │   ├── quill/
│   │   │   │   │   ├── quill.js
│   │   │   │   │   ├── quill.snow.css
│   │   │   │   │   ├── quill.bubble.css
│   │   │   │   │   ├── quill.min.js
│   │   │   │   │   ├── quill.min.js.map
│   │   │   │   │   ├── quill.core.css
│   │   │   │   │   └── quill.core.js
│   │   │   │   ├── echarts/
│   │   │   │   │   ├── echarts.common.js.map
│   │   │   │   │   ├── echarts.js
│   │   │   │   │   ├── echarts.esm.min.mjs
│   │   │   │   │   ├── echarts.common.min.js
│   │   │   │   │   ├── echarts.esm.mjs.map
│   │   │   │   │   ├── echarts.esm.js
│   │   │   │   │   ├── echarts.simple.js.map
│   │   │   │   │   ├── package.json
│   │   │   │   │   ├── echarts.common.js
│   │   │   │   │   ├── echarts.js.map
│   │   │   │   │   ├── echarts.esm.js.map
│   │   │   │   │   ├── echarts.simple.min.js
│   │   │   │   │   ├── echarts.esm.mjs
│   │   │   │   │   ├── echarts.simple.js
│   │   │   │   │   ├── echarts.min.js
│   │   │   │   │   └── echarts.esm.min.js
│   │   │   │   │   ├── extension/
│   │   │   │   │   │   ├── dataTool.js
│   │   │   │   │   │   ├── dataTool.js.map
│   │   │   │   │   │   ├── bmap.js
│   │   │   │   │   │   ├── dataTool.min.js
│   │   │   │   │   │   ├── bmap.js.map
│   │   │   │   │   │   └── bmap.min.js
│   │   │   │   ├── aos/
│   │   │   │   │   ├── aos.esm.js
│   │   │   │   │   ├── aos.css
│   │   │   │   │   ├── aos.cjs.js
│   │   │   │   │   ├── aos.js
│   │   │   │   │   └── aos.js.map
│   │   ├── templates/
│   │   │   ├── traffic_analysis.html
│   │   │   ├── base.html
│   │   │   ├── register.html
│   │   │   ├── login.html
│   │   │   ├── dashboard.html
│   │   │   ├── test.html
│   │   │   └── landing.html
