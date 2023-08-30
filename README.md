# Apple Media Accessibility API
Collecting resources around Apples Media Accessibility Framework

[Apple Media Accessibility Framework](https://developer.apple.com/documentation/mediaaccessibility/)

FCC requirements for captions

## FCC Closed Caption Requirements

 [FCC Source](https://www.ecfr.gov/current/title-47/chapter-I/subchapter-C/part-79/subpart-B/section-79.103#p-79.103(c))

  - Font color: 8 Colors (with mandated subset)
    https://developer.apple.com/documentation/mediaaccessibility/1464828-macaptionappearancecopyforegroun
  - Font opacity: 0-100%
    https://developer.apple.com/documentation/mediaaccessibility/1464887-macaptionappearancegetforeground
  - Font Size: 50% to 400% 
    https://developer.apple.com/documentation/mediaaccessibility/1464820-macaptionappearancegetrelativech 
    scale from 0.0 to 2.0
  - Fonts: 8 
    https://developer.apple.com/documentation/mediaaccessibility/1464816-macaptionappearancecopyfontdescr
  - Background (of text) opacity: 0 to 100%
    https://developer.apple.com/documentation/mediaaccessibility/1464840-macaptionappearancegetbackground
  - Background color: 8 (with mandated subset)
    https://developer.apple.com/documentation/mediaaccessibility/1464822-macaptionappearancecopybackgroun
  - Window (box encompassing Text) color: 8
    https://developer.apple.com/documentation/mediaaccessibility/1464842-macaptionappearancecopywindowcol
  - Window opacity: 0 to 100% 
    https://developer.apple.com/documentation/mediaaccessibility/1464844-macaptionappearancegetwindowopac
  - Language: according to tracks present
    https://developer.apple.com/documentation/mediaaccessibility/1464855-macaptionappearancecopyselectedl
  - Character Edge Style: 4 (with mandated subset)
    https://developer.apple.com/documentation/mediaaccessibility/1464824-macaptionappearancegettextedgest
  - Preview and setting retention: preview action and retain final as changed by user
    -> Managed in device _Settings > Accessibility > Subtitles & Captioning > Style_
  - Reset option
    -> Managed in device _Settings > Accessibility > Subtitles & Captioning > Style_
  - Presentation mode: all at once (pop-on), roll up, paint-on
    -> defined in TTML document
