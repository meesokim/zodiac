[]CodeWarriorでのコンパイルについて

	　スクリプトに対応していないので，コンパイル前に，以下の作業を手動で
	行ってください．

	・zodiac/CWproject/conifg.h のエ イ リア スを zodiac/ に置 く．
	・zodiac/libmd/sdl/md_depend.h のエイリアスを zodiac/libmd/ に置く．
	・zodiac/libmd/md.h.in をコピーして md.h にリネーム．
	・md.h を開いて文字列 "@MD_DIR_LAYOUT@" を"MD_MAC"に置換する．



Mar 11,2002 Written by W.Kitada
