## Audio Tracker demo

using **Alphonso SDK** (third) example of capturing spoken phonetic alphabet.

### Layout
- Intro.
- Method.
- APK.
- Screens.
- Audio files.

Link to Google Play store game app:
[Victoria Aztec Hidden Object ](https://play.google.com/store/apps/details?id=com.fgl.adrianmarik.victoriaaztecsfree)

Google Play app store listing integration statement:
```markdown
This app is integrated with Alphonso software. Subject to your permission, the Alphonso software receives short duration audio samples from the microphone on your device. The audio samples never leave your device, but are irreversibly encoded (hashed) into digital "fingerprints." The fingerprints are compared off-device to commercial content (e.g., TV, OTT programming, ads music etc.). If a match is found, then appropriate recommendation for content or ads may be delivered to your mobile device. The Alphonso software only matches against known audio content and does not recognize or understand human conversations or other sounds.
```

```markdown
alphonso.xml (edited)
`<map>
  <string name="server_domain">http://tkacr197.alphonso.tv</string>
  <boolean name="audio_file_upload_flag" value="false" />
  <string name="acr_db_filename">acr.a.2.1.4.db.zero.mp3</string>
  <boolean name="capture_power_optimization_mode" value="true" />
  <int name="acr_shift" value="0" />
  <long name="capture_duration_ms" value="4000" />
  <long name="capture_scenario_sleep_interval" value="8" />
  <string name="acr_db_file_dir">/data/user/0/com.ettaapps.blackbox/files</string>
  <long name="capture_scenario_sleep_interval_livetv_match" value="60" />
  <int name="capture_prebuffer_size" value="0" />
  <int name="db_max_records" value="1000" />
  <string name="acr_db_file_abs_path">/data/user/0/com.ettaapps.blackbox/files/acr.a.2.1.4.db.zero.mp3</string>
  <boolean name="limit_ad_tracking_flag" value="false" />
  <string name="server_port">4432</string>
  <long name="capture_scenario_sleep_interval_max" value="160" />
  <long name="location_poll_interval" value="15" />
</map>`
```

_Images_

![Completed audio join file](https://github.com/kaputnikGo/kaputnikGo.github.io/blob/master/images/Screenshot_3-step-join-speed-redux.png)

