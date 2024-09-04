shorten_names <- function(name) {
  name %>%
    str_replace_all("in_which_language_do_you_prefer_to_express_yourself", "lang_pref") %>%
    str_replace_all("which_specific_subjects_within_statistical_or_scientific_research_pique_your_interest_", "interest_") %>%
    str_replace_all("which_programming_language_s_interest_you_", "prog_lang_") %>%
    str_replace_all("interest_", "int_") %>%
    str_replace_all("statistical_tests_parametric_and_non_parametric", "stat_tests") %>%
    str_replace_all("linear_modeling_regression_analysis_glm_multilevel_etc", "linear_modeling") %>%
    str_replace_all("longitudinal_analysis_survival_panel_time_series_etc", "long_analysis") %>%
    str_replace_all("data_visualization", "datavis") %>%
    str_replace_all("bayesian_statistics", "bayesian") %>%
    str_replace_all("multivariate_statistics_pca_cluster_sem_etc", "multivar_stats") %>%
    str_replace_all("survey_design_and_analysis", "survey_design") %>%
    str_replace_all("network_analysis", "network") %>%
    str_replace_all("spatial_statistics", "spatial") %>%
    str_replace_all("scientific_simulation", "sci_sim") %>%
    str_replace_all("report_production", "report_prod") %>%
    str_replace_all("scientific_publication_reproducibility_version_control", "sci_pub") %>%
    str_replace_all("prog_lang_", "lang_") %>%
    str_replace_all("on_a_scale_from_1_no_experience_to_5_expert_what_is_your_current_proficiency_level_in_programming_using_the_", "prof_") %>%
    str_replace_all("would_you_like_to_provide_any_additional_information_or_context_about_your_programming_experience", "prog_exp_context") %>%
    str_replace_all("how_often_would_you_be_interested_in_participating_in_data_meetups", "meetup_freq") %>%
    str_replace_all("would_you_like_to_be_mentored_if_so_we_would_love_to_hear_more_about_your_interests_and_needs_in_the_comment_section_discipline_needs_and_any_useful_information", "mentee_info") %>%
    str_replace_all("_comment$", "_cmt") %>%
    str_replace_all("are_you_open_to_the_possibility_of_mentoring_another_ph_d_student_your_participation_is_entirely_voluntary_and_you_may_decline_later_if_you_do_not_feel_it_aligns_with_your_current_commitments_please_let_us_know_more_about_you_in_the_comment_section_subject_or_field_you_are_comfortable_mentoring_in", "mentor_info") %>%
    str_replace_all("we_are_excited_to_introduce_a_new_initiative_aimed_at_fostering_collaboration_and_knowledge_sharing_within_our_university_community_we_are_creating_a_local_online_communication_platform_where_individuals_can_freely_engage_in_discussions_seek_answers_to_questions_and_exchange_ideas_related_to_statistics_and_research_your_participation_will_enrich_this_platform_and_contribute_to_a_vibrant_community_of_learners_and_researchers", "platform_intro") %>%
    str_replace_all("would_you_like_to_join_this_local_online_communication_platform_at_the_university_where_everyone_is_free_to_ask_and_answer_questions_and_exchange_ideas_about_statistics_and_research", "join_platform") %>%
    str_replace_all("the_communitys_aim_will_also_be_to_bring_together_as_many_free_educational_resources_as_possible_so_that_everyone_can_learn_for_themselves_if_they_wish_you_dont_have_to_be_the_author_of_these_resources_to_share_them_as_long_as_they_are_freely_and_legally_available_would_you_like_to_share_free_teaching_materials_if_so_let_us_know_in_the_comments_section_what_type_of_resource_you_found", "share_resources") %>%
    str_replace_all("if_you_have_expressed_int_in_mentorship_seeking_a_mentor_mentee_sharing_resources_joining_an_online_community_or_wish_to_be_contacted_later_we_would_love_to_stay_connected_please_feel_free_to_leave_your_email_address_below_your_email_will_only_be_used_for_the_purposes_youve_indicated_and_we_respect_your_privacy_thank_you_for_your_willingness_to_engage_further", "contact_email")
}

# # Define a function to shorten column names
# shorten_names <- function(name) {
#   name %>%
#     str_replace_all("in_which_language_do_you_prefer_to_express_yourself", "lang_pref") %>%
#     str_replace_all("interest_", "int_") %>%
#     str_replace_all("statistical_tests_parametric_and_non_parametric", "stat_tests") %>%
#     str_replace_all("linear_modeling_regression_analysis_glm_multilevel_etc", "linear_modeling") %>%
#     str_replace_all("longitudinal_analysis_survival_panel_time_series_etc", "long_analysis") %>%
#     str_replace_all("data_visualization", "datavis") %>%
#     str_replace_all("bayesian_statistics", "bayesian") %>%
#     str_replace_all("multivariate_statistics_pca_cluster_sem_etc", "multivar_stats") %>%
#     str_replace_all("survey_design_and_analysis", "survey_design") %>%
#     str_replace_all("network_analysis", "network") %>%
#     str_replace_all("spatial_statistics", "spatial") %>%
#     str_replace_all("scientific_simulation", "sci_sim") %>%
#     str_replace_all("report_production", "report_prod") %>%
#     str_replace_all("scientific_publication_reproducibility_version_control", "sci_pub") %>%
#     str_replace_all("prog_lang_", "lang_") %>%
#     str_replace_all("on_a_scale_from_1_no_experience_to_5_expert_what_is_your_current_proficiency_level_in_programming_using_the_", "prof_") %>%
#     str_replace_all("would_you_like_to_provide_any_additional_information_or_context_about_your_programming_experience", "prog_exp_context") %>%
#     str_replace_all("how_often_would_you_be_interested_in_participating_in_data_meetups", "meetup_freq") %>%
#     str_replace_all("would_you_like_to_be_mentored_if_so_we_would_love_to_hear_more_about_your_interests_and_needs_in_the_comment_section_discipline_needs_and_any_useful_information", "mentee_info") %>%
#     str_replace_all("_comment$", "_cmt") %>%
#     str_replace_all("are_you_open_to_the_possibility_of_mentoring_another_ph_d_student_your_participation_is_entirely_voluntary_and_you_may_decline_later_if_you_do_not_feel_it_aligns_with_your_current_commitments_please_let_us_know_more_about_you_in_the_comment_section_subject_or_field_you_are_comfortable_mentoring_in", "mentor_info") %>%
#     str_replace_all("we_are_excited_to_introduce_a_new_initiative_aimed_at_fostering_collaboration_and_knowledge_sharing_within_our_university_community_we_are_creating_a_local_online_communication_platform_where_individuals_can_freely_engage_in_discussions_seek_answers_to_questions_and_exchange_ideas_related_to_statistics_and_research_your_participation_will_enrich_this_platform_and_contribute_to_a_vibrant_community_of_learners_and_researchers", "platform_intro") %>%
#     str_replace_all("would_you_like_to_join_this_local_online_communication_platform_at_the_university_where_everyone_is_free_to_ask_and_answer_questions_and_exchange_ideas_about_statistics_and_research", "join_platform") %>%
#     str_replace_all("the_communitys_aim_will_also_be_to_bring_together_as_many_free_educational_resources_as_possible_so_that_everyone_can_learn_for_themselves_if_they_wish_you_dont_have_to_be_the_author_of_these_resources_to_share_them_as_long_as_they_are_freely_and_legally_available_would_you_like_to_share_free_teaching_materials_if_so_let_us_know_in_the_comments_section_what_type_of_resource_you_found", "share_resources") %>%
#     str_replace_all("if_you_have_expressed_int_in_mentorship_seeking_a_mentor_mentee_sharing_resources_joining_an_online_community_or_wish_to_be_contacted_later_we_would_love_to_stay_connected_please_feel_free_to_leave_your_email_address_below_your_email_will_only_be_used_for_the_purposes_youve_indicated_and_we_respect_your_privacy_thank_you_for_your_willingness_to_engage_further", "contact_email")
# }
# 
# 
