big ass .hed file
i think i heard that having too many phonemes in one hed file hurts the synthisis but this is mostly a test to see if i could do cross synthisis in a similar way to how i think synth V does it, as apposed to how aichi's voicebank works
also this is my first time using github please forgive me if im dumb or anything idk

the phonemes are "aa,ae,ah,ao,aw,ax,ay,eh,er,ey,ih,iy,ow,oy,uh,uw,a,i,u,e,o,A,I,U,E,O,m,n,ng,p,tt,ch,k,b,dd,jh,g,ff,th,s,sh,hh,v,dh,z,zh,l,rr,y,w,dr,tr,el,em,en,q,dx,vf,N,f,cl,t,d,j,ts,h,ry,ky,py,ny,hy,my,gy,by,r,br,pau,sil,axh,exh"

vowels are seperated and consonant phonemes are usualy shared and acent is handled via context based on if the vowel next to it is jpn or not. the exeptions to this rule are the "r" phoneme, which used in english is "rr", the "f" phoneme which is "ff" in english, and the "t" and "d' phoneme, which are "tt" and "dd" in english
tables are kinda a mess so for training just use phonemes for peice of mind. when using labtoust for japanese select the "5 vowel system" and add "N" to the vowels in the languages file.
when converting a voicebank from either utautautau's or intunist's hed files, go into both the .lab files and find and replace the changed phonemes. then do the same for the ust by opening them up as a txt file.
its worth it to know that if you're converting from a intunist english vb its not one to one, as i didnt base this hed file off of theirs. that being said if you want any non english or japanese phomemes like a trilled r or a Fricative r use theirs. https://github.com/intunist/nnsvs-english-support

but yeah this is mostly a test and i havent even seen if it trains in the first place so yeah

if you also want the planing sheet here you go
https://docs.google.com/spreadsheets/d/17rplh1wRRAxZpGVXjSKhnYphF1pKojwcGIOSQszepKg/edit?usp=sharing
