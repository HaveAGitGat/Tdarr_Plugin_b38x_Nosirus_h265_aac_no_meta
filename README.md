# Tdarr_Plugin_b38x_Nosirus_h265_aac_no_meta
If the file is not in h265 it will be trancoded into h265 using the following command '-e x265 -q 22 --encoder-preset slow --all-audio --all-subtitles copy:aac -E fdk_aac -Q 4 -x aq-mode=3'. If no aac, aac track will be added. Subtitles are kept. Metadata is removed.
