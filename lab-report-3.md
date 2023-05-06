# Lab Report 3 #
*For this assignment, I chose the* `find` *command*

## Find by path: `find [dir] -path [path]`
Source: https://www.diskinternals.com/linux-reader/bash-find-command/

Example 1:
```
[cs15lsp23iu@ieng6-201]:stringsearch-data:270$ find ./technical/ -ipath "*Media*"     
./technical/government/Media
./technical/government/Media/5_Legal_Groups.txt
./technical/government/Media/AP_LawSchoolDebts.txt
./technical/government/Media/A_Perk_of_Age.txt
./technical/government/Media/A_helping_hand.txt
./technical/government/Media/Abuse_penalties.txt
./technical/government/Media/Advocate_for_Poor.txt
./technical/government/Media/Aid_Gets_7_Million.txt
./technical/government/Media/All_May_Have_Justice.txt
./technical/government/Media/Annual_Fee.txt
./technical/government/Media/Anthem_Payout.txt
./technical/government/Media/Assuring_Underprivileged.txt
./technical/government/Media/Attorney_gives_his_time.txt
./technical/government/Media/Avoids_Budget_Cut.txt
./technical/government/Media/Barnes_Volunteers.txt
./technical/government/Media/Barnes_new_job.txt
./technical/government/Media/Barnes_pro_bono.txt
./technical/government/Media/Barr_sharpening_ax.txt
./technical/government/Media/BergenCountyRecord.txt
./technical/government/Media/Bias_on_the_Job.txt
./technical/government/Media/Boone_legal_service.txt
./technical/government/Media/Bridging_legal_aid_gap.txt
./technical/government/Media/BusinessWire.txt
./technical/government/Media/BusinessWire2.txt
./technical/government/Media/Butler_Co_attorneys.txt
./technical/government/Media/Campaign_Pays.txt
./technical/government/Media/City_Council_Budget.txt
./technical/government/Media/Civil_Matters.txt
./technical/government/Media/CommercialAppealMemphis2.txt
./technical/government/Media/Commercial_Appeal.txt
./technical/government/Media/Coup_Reshapes_Legal_Aid.txt
./technical/government/Media/Court_Keeps_Judge_From.txt
./technical/government/Media/Crains_New_York_Business.txt
./technical/government/Media/Disaster_center.txt
./technical/government/Media/Do-it-yourself_divorce.txt
./technical/government/Media/Domestic_Violence_Ruling.txt
./technical/government/Media/Domestic_violence_aid.txt
./technical/government/Media/Donald_Hilliker.txt
./technical/government/Media/Entities_Merge.txt
./technical/government/Media/Eviction_law.txt
./technical/government/Media/FY_04_Budget_Outlook.txt
./technical/government/Media/Farm_workers.txt
./technical/government/Media/Federal_agency.txt
./technical/government/Media/Few_who_need.txt
./technical/government/Media/Fire_Victims_Sue.txt
./technical/government/Media/Firm_to_the_Poor_Needs_Help.txt
./technical/government/Media/FortWorthStarTelegram.txt
./technical/government/Media/Free_Legal_Assistance.txt
./technical/government/Media/Free_legal_service.txt
./technical/government/Media/Funding_May_Limit.txt
./technical/government/Media/Funding_cuts_force.txt
./technical/government/Media/Funds_Shortage.txt
./technical/government/Media/Ginny_Kilgore.txt
./technical/government/Media/Good_guys_reward.txt
./technical/government/Media/Greedy_Generous.txt
./technical/government/Media/GreensburgDailyNews.txt
./technical/government/Media/Hard_to_Get.txt
./technical/government/Media/Helping_Hands.txt
./technical/government/Media/Helping_Out.txt
./technical/government/Media/Higher_Registration_Fees.txt
./technical/government/Media/Higher_court.txt
./technical/government/Media/IOLTA_INTEREST_RATE.txt
./technical/government/Media/It_Pays_to_Know.txt
./technical/government/Media/Justice_for_all.txt
./technical/government/Media/Justice_requests.txt
./technical/government/Media/Kiosks_for_court_forms.txt
./technical/government/Media/Law-school_grads.txt
./technical/government/Media/Law_Award_from_College.txt
./technical/government/Media/Law_Schools.txt
./technical/government/Media/Lawyer_Web_Survey.txt
./technical/government/Media/Legal-aid_chief.txt
./technical/government/Media/Legal_Aid_Society.txt
./technical/government/Media/Legal_Aid_attorney.txt
./technical/government/Media/Legal_Aid_campaign.txt
./technical/government/Media/Legal_Aid_in_Clay_County.txt
./technical/government/Media/Legal_Aid_looks_to_legislators.txt
./technical/government/Media/Legal_hotline.txt
./technical/government/Media/Legal_services_for_poor.txt
./technical/government/Media/Legal_system_fails_poor.txt
./technical/government/Media/Library_Lawyers.txt
./technical/government/Media/Lindsays_legacy.txt
./technical/government/Media/Local_Attorneys.txt
./technical/government/Media/Lockyer_Warns.txt
./technical/government/Media/Low-income_children.txt
./technical/government/Media/Major_Changes.txt
./technical/government/Media/Making_a_case.txt
./technical/government/Media/Marylands_Legal_Aid.txt
./technical/government/Media/NJ_Legal_Services.txt
./technical/government/Media/New_Online_Resources.txt
./technical/government/Media/New_funding_sources.txt
./technical/government/Media/Nonprofit_Buys.txt
./technical/government/Media/Oregon_Poor.txt
./technical/government/Media/Owning_a_Piece.txt
./technical/government/Media/Paralegal_Honored.txt
./technical/government/Media/Philly_Lawyers.txt
./technical/government/Media/Politician_Practices.txt
./technical/government/Media/Poor_Lacking_Legal_Aid.txt
./technical/government/Media/Poverty_Lawyers.txt
./technical/government/Media/Pro-bono_road_show.txt
./technical/government/Media/Pro_Bono_Services.txt
./technical/government/Media/Program_Lodges.txt
./technical/government/Media/Providing_Legal_Aid.txt
./technical/government/Media/Raising_the_Bar.txt
./technical/government/Media/Rental_rules.txt
./technical/government/Media/Retirement_Has_Its_Appeal.txt
./technical/government/Media/RoanokeTimes.txt
./technical/government/Media/Rumble_in_the_Bronx.txt
./technical/government/Media/Self-Help_Website.txt
./technical/government/Media/Service_Agency.txt
./technical/government/Media/State_funding.txt
./technical/government/Media/Supporting_Legal_Center.txt
./technical/government/Media/Survey.txt
./technical/government/Media/Targeting_Domestic_Violence.txt
./technical/government/Media/Terrorist_Attack.txt
./technical/government/Media/Texas_Lawyer.txt
./technical/government/Media/Texas_Supreme_Court.txt
./technical/government/Media/The_Bend_Bulletin.txt
./technical/government/Media/The_Columbian.txt
./technical/government/Media/The_State_of_Pro_Bono.txt
./technical/government/Media/Too_Crucial_to_Take_Cut.txt
./technical/government/Media/Towson_Attorney.txt
./technical/government/Media/Understanding.txt
./technical/government/Media/Unusual_Woodburn.txt
./technical/government/Media/Using_Tech_Tools.txt
./technical/government/Media/Valley_Needing_Legal_Services.txt
./technical/government/Media/Volunteers_Step_Up.txt
./technical/government/Media/Weak_economy.txt
./technical/government/Media/Wilmington_lawyer.txt
./technical/government/Media/Wingates_winds.txt
./technical/government/Media/Workers_aid_center.txt
./technical/government/Media/Working_for_Free.txt
./technical/government/Media/agency_expands.txt
./technical/government/Media/balance_scales_of_justice.txt
./technical/government/Media/defend_yourself.txt
./technical/government/Media/families_saved.txt
./technical/government/Media/fight_domestic_abuse.txt
./technical/government/Media/grants_fail_to_come.txt
./technical/government/Media/help_rent-to-own_tenants.txt
./technical/government/Media/highlight_Senior_Day.txt
./technical/government/Media/less_legal_aid.txt
./technical/government/Media/man_on_national_team.txt
./technical/government/Media/not_accessible_to_disabled.txt
./technical/government/Media/predatory_loans.txt
./technical/government/Media/pro_bono_efforts.txt
./technical/government/Media/residents_sue_city.txt
./technical/government/Media/water_fees.txt
```

Example 2:
```
[cs15lsp23iu@ieng6-201]:stringsearch-data:275$ find ./technical/ -ipath "*legal*"     
./technical/government/About_LSC/LegalServCorp_v_VelazquezDissent.txt
./technical/government/About_LSC/LegalServCorp_v_VelazquezOpinion.txt
./technical/government/About_LSC/LegalServCorp_v_VelazquezSyllabus.txt
./technical/government/About_LSC/ONTARIO_LEGAL_AID_SERIES.txt
./technical/government/Media/5_Legal_Groups.txt
./technical/government/Media/Boone_legal_service.txt
./technical/government/Media/Bridging_legal_aid_gap.txt
./technical/government/Media/Coup_Reshapes_Legal_Aid.txt
./technical/government/Media/Free_Legal_Assistance.txt
./technical/government/Media/Free_legal_service.txt
./technical/government/Media/Legal-aid_chief.txt
./technical/government/Media/Legal_Aid_Society.txt
./technical/government/Media/Legal_Aid_attorney.txt
./technical/government/Media/Legal_Aid_campaign.txt
./technical/government/Media/Legal_Aid_in_Clay_County.txt
./technical/government/Media/Legal_Aid_looks_to_legislators.txt
./technical/government/Media/Legal_hotline.txt
./technical/government/Media/Legal_services_for_poor.txt
./technical/government/Media/Legal_system_fails_poor.txt
./technical/government/Media/Marylands_Legal_Aid.txt
./technical/government/Media/NJ_Legal_Services.txt
./technical/government/Media/Paralegal_Honored.txt
./technical/government/Media/Poor_Lacking_Legal_Aid.txt
./technical/government/Media/Providing_Legal_Aid.txt
./technical/government/Media/Supporting_Legal_Center.txt
./technical/government/Media/Valley_Needing_Legal_Services.txt
./technical/government/Media/less_legal_aid.txt
```

## Find by last modified date: `find [dir] -mtime [+/-][days]`
https://www.thegeekdiary.com/7-useful-find-command-examples-to-locate-files-to-remove-when-a-filesystem-is-full/


## Find by size in kB: `find [dir] -size +[bytes][size char]`
https://www.thegeekdiary.com/7-useful-find-command-examples-to-locate-files-to-remove-when-a-filesystem-is-full/
Example 1:
```
[cs15lsp23iu@ieng6-201]:stringsearch-data:289$ find ./technical/ -size +200k
./technical/911report/chapter-13.4.txt
./technical/911report/chapter-13.5.txt
./technical/911report/chapter-3.txt
./technical/government/About_LSC/commission_report.txt
./technical/government/Env_Prot_Agen/bill.txt
./technical/government/Gen_Account_Office/GovernmentAuditingStandards_yb2002ed.txt    
./technical/government/Gen_Account_Office/Statements_Feb28-1997_volume.txt
./technical/government/Gen_Account_Office/d01591sp.txt
```

Example 2:
```
[cs15lsp23iu@ieng6-201]:stringsearch-data:292$ find ./technical/ -size -5  
./technical/government/Media/Campaign_Pays.txt
./technical/government/Media/Court_Keeps_Judge_From.txt
./technical/government/Media/Fire_Victims_Sue.txt
./technical/government/Media/Helping_Hands.txt
./technical/government/Media/It_Pays_to_Know.txt
./technical/government/Media/Justice_requests.txt
./technical/government/Media/Lawyer_Web_Survey.txt
./technical/government/Media/Self-Help_Website.txt
./technical/government/Media/Wilmington_lawyer.txt
./technical/plos/pmed.0020028.txt
./technical/plos/pmed.0020048.txt
./technical/plos/pmed.0020082.txt
./technical/plos/pmed.0020120.txt
./technical/plos/pmed.0020157.txt
./technical/plos/pmed.0020191.txt
./technical/plos/pmed.0020192.txt
./technical/plos/pmed.0020226.txt
```

## Find with or: `find [dir] [condition 1] -or [condition 2]`
https://math2001.github.io/article/bashs-find-command/