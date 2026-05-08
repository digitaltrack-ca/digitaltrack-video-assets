# License Tracking

Store source/license evidence for every track here.

## Verification Standard

Do not treat a downloaded MP3 alone as proof of permitted commercial use.

For Pixabay-based tracks, `verified` should mean:

1. The exact Pixabay track page URL is recorded.
2. The general Pixabay license reference is recorded.
3. The checked date is recorded.
4. Any special note is recorded when the track page mentions Content ID or other platform-specific caveats.

Until all four are present, keep the catalog entry as `needs_verification`.

## Reference Links

- Pixabay License Summary: https://pixabay.com/service/license-summary/
- Pixabay FAQ: https://pixabay.com/service/faq/

Pixabay says content can be used for free, without attribution, and modified into new works, including commercial use, subject to prohibited uses and third-party rights checks.

## Recommended File Naming

- `track-id_source-url.txt`
- `track-id_license.txt`
- `track-id_attribution.txt`

## Current Track Source Log

- alexgrohl-no-copyright-music-bounce-on-it-184234: https://pixabay.com/music/future-bass-no-copyright-music-bounce-on-it-184234/
- apalonbeats-phonk-phonks-519293: https://pixabay.com/music/phonk-phonk-phonks-519293/
- atlasaudio-energetic-energetic-music-507828: https://pixabay.com/music/upbeat-energetic-energetic-music-507828/
- bombinsound-corporate-advertising-512486: https://pixabay.com/music/corporate-corporate-advertising-512486/
- joyinsound-chasing-success-shaping-the-future-507158: https://pixabay.com/music/traditional-jazz-bebop-coffee-shop-517090/
- leberch-hip-hop-516914: https://pixabay.com/music/beats-hip-hop-516914/
- loksii-no-copyright-music-211881: https://pixabay.com/music/beats-no-copyright-music-211881/
- monume-background-music-519228: https://pixabay.com/music/trap-background-music-519228/
- monume-summer-519246: https://pixabay.com/music/beats-summer-519246/
- moodmode-no-copyright-music-201745: https://pixabay.com/music/funk-no-copyright-music-201745/
- pink_sound-golden-waves-tropical-house-instrumental-background-music-1-minute-520794: https://pixabay.com/music/dance-golden-waves-tropical-house-instrumental-background-music-1-minute-520794/
- prettyjohn1-corporate-corporate-music-483403: https://pixabay.com/music/corporate-corporate-corporate-music-483403/
- prettyjohn1-hip-hop-514999: https://pixabay.com/music/beats-hip-hop-514999/
- prettyjohn1-no-copyright-music-498106: https://pixabay.com/music/funk-no-copyright-music-201745/
- sigmamusicart-news-news-background-520540: https://pixabay.com/music/corporate-news-news-background-520540/
- the_mountain-upbeat-background-483308: https://pixabay.com/music/upbeat-upbeat-background-483308/
- universfield-motivating-indie-rock-30s-240055: https://pixabay.com/music/upbeat-motivating-indie-rock-30s-240055/

## Evidence Added

The following proof files were added from the local working folder and are currently treated as sufficient internal verification evidence.

- `background_monume_license.txt`
- `bounce_on_it_alexgrohl_license.txt`
- `energetic_atlasaudio_license.txt`
- `golden_waves_pink_sound_license.txt`
- `hip_hop_leberch_license.txt`
- `motivating_indie_rock_30s_universfield_license.txt`
- `news_background_sigmamusicart_license.txt`
- `no_copyright_loksii_license.txt`
- `no_copyright_moodmode_license.txt`
- `phonks_apalonbeats_license.txt`
- `summer_monume_license.txt`
- `upbeat_background_the_mountain_license.txt`

The following supporting files were also added and accepted as supporting evidence where a plain-text certificate was not available at the time:

- `corporate_advertising_bombinsound_support.png`
- `corporate_prettyjohn1_support.pdf`
- `hip_hop_prettyjohn1_support.pdf`

## Still Pending

These tracks still need exact matching proof before they should be treated as fully verified:

- `chasing_success_joyinsound`
  Current local certificate file is `chasing_success_joyinsound_unverified_license.txt`, but it points to Pixabay asset ID `517090`, not the music file ID `507158`.
- `no_copyright_prettyjohn1`
  No exact matching certificate/support file was added yet.

## What To Do Next

- Add an exact matching certificate or source proof for `chasing_success_joyinsound`.
- Add exact matching proof for `no_copyright_prettyjohn1`.
- If better Pixabay certificates become available later for the screenshot/PDF-backed tracks, replace the support files with certificate text files.
