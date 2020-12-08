## Pagerank-Updated

This is an updated version of pagerank utilizing a keyword search showing similar/related topics. This is based off the original Pagerank search from "Deeper Inside Pagerank". 

# Search Results
montypatterson@Montys-MacBook-Pro-2 11b_word2vec_coding % python pagerank2.py  --data=./lawfareblog.csv.gz --search_query='weapons'    
INFO:root:rank=0 pagerank=0.004571518860757351 url=www.lawfareblog.com/why-did-you-wait-moral-emptiness-and-drone-strikes
INFO:root:rank=1 pagerank=0.0031107424292713404 url=www.lawfareblog.com/dc-district-court-dismisses-journalists-drone-lawsuit
INFO:root:rank=2 pagerank=0.0020231129601597786 url=www.lawfareblog.com/revived-cia-drone-strike-program-comments-new-policy
INFO:root:rank=3 pagerank=0.0019667143933475018 url=www.lawfareblog.com/us-court-appeals-dc-circuit-dismisses-suit-over-us-drone-strike
INFO:root:rank=4 pagerank=0.001178761012852192 url=www.lawfareblog.com/iran-shoots-down-us-drone-domestic-and-international-legal-implications
INFO:root:rank=5 pagerank=0.0011619674041867256 url=www.lawfareblog.com/slaughterbots-and-other-anticipated-autonomous-weapons-problems
INFO:root:rank=6 pagerank=0.0011276121949777007 url=www.lawfareblog.com/german-courts-weigh-legal-responsibility-us-drone-strikes
INFO:root:rank=7 pagerank=0.0008373793680220842 url=www.lawfareblog.com/shift-jsoc-drone-strikes-does-not-mean-cia-has-been-sidelined
INFO:root:rank=8 pagerank=0.0007870369008742273 url=www.lawfareblog.com/atomwaffen-division-member-pleads-guilty-firearms-charge
INFO:root:rank=9 pagerank=0.0007856971933506429 url=www.lawfareblog.com/waiving-imminent-threat-test-cia-drone-strikes-pakistan

#**Search Results pt.2**
 montypatterson@Montys-MacBook-Pro-2 11b_word2vec_coding % python pagerank2.py  --data=./lawfareblog.csv.gz --search_query='national security'
INFO:root:rank=0 pagerank=0.007860383950173855 url=www.lawfareblog.com/rational-security-lonely-amigo-edition
INFO:root:rank=1 pagerank=0.006913956254720688 url=www.lawfareblog.com/mueller-report-and-national-security-investigations-and-prosecutions
INFO:root:rank=2 pagerank=0.006272614933550358 url=www.lawfareblog.com/what-british-government-really-thinks
INFO:root:rank=3 pagerank=0.0042897374369204044 url=www.lawfareblog.com/judicial-review-decisions-kill-american-citizens-under-aumf-most-important-case-you-missed-last-week
INFO:root:rank=4 pagerank=0.004190244246274233 url=www.lawfareblog.com/document-government-briefing-opposing-supreme-court-review-al-alwi
INFO:root:rank=5 pagerank=0.004178560804575682 url=www.lawfareblog.com/silence-and-use-force-international-law
INFO:root:rank=6 pagerank=0.00415109982714057 url=www.lawfareblog.com/un-security-council-resolution-protecting-people-disabilities-armed-conflict
INFO:root:rank=7 pagerank=0.003962312359362841 url=www.lawfareblog.com/announcing-9th-national-security-law-workshop
INFO:root:rank=8 pagerank=0.003961699549108744 url=www.lawfareblog.com/announcing-10th-national-security-law-workshop
INFO:root:rank=9 pagerank=0.0035850685089826584 url=www.lawfareblog.com/international-terrorism-prosecutions-2018-wrap

The code can be found in Pagerank2.py in this repo.
