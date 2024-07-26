## WorldQuant 因子整理

### Region:GLB

##### Dataset: **Nonlinear adaptive model**, Dataset ID: **"other176"**

潜在因子列表：

- ts_zscore(oth176_lmt_close_eq_score, 12)
- oth176_malta_eq_score
- oth176_maltahc_eq_score
- oth176_eq_hedge
- oth176_hc_eq_hedge
- oth176_eq_medium
- oth176_lmt_open_eq_score
- oth176_eq_seasonality
- oth176_hc_eq_medium
- oth176_hc_eq_seasonality

**Fundamental Analyst Estimates** "analyst69"

| Expressions                                |
| ------------------------------------------ |
| ts_zscore(anl69_sales_best_eeps_nxt_yr,12) |
| ts_zscore(anl69_cps_best_eeps_nxt_yr,12)   |
| ts_zscore(anl69_roa_best_eeps_cur_yr,12)   |
| ts_zscore(anl69_pe_best_eeps_cur_yr,12)    |
| ts_zscore(anl69_eps_best_eeps_cur_yr,12)   |
| ts_zscore(anl69_sales_best_eeps_cur_yr,12) |
| ts_zscore(anl69_roe_best_eeps_cur_yr,12)   |
| ts_zscore(anl69_ndebt_best_eeps_cur_yr,12) |
| ts_zscore(anl69_cps_best_eeps_cur_yr,12)   |
| ts_zscore(anl69_net_best_eeps_cur_yr,12)   |

**fundamental17**

| fitness | sharpe | expression                           |
| ------- | ------ | ------------------------------------ |
| 0.83    | 1.88   | ts_zscore(fnd17_fcfmtt,12)           |
| 0.75    | 1.72   | ts_zscore(fnd17_ebitda2ev,12)        |
| 0.71    | 1.66   | ts_zscore(fnd17_ebitda2ev_ttm,12)    |
| 0.81    | 1.6    | ts_zscore(fnd17_dai,12)              |
| 0.68    | 1.59   | ts_zscore(fnd17_ebitda2ev_a,12)      |
| 0.61    | 1.53   | ts_zscore(fnd17_rhsfcfmtt,12)        |
| 0.6     | 1.42   | ts_zscore(fnd17_yield,12)            |
| 0.53    | 1.33   | ts_zscore(fnd17_tbemtt,12)           |
| 0.52    | 1.25   | ts_zscore(fnd17_qtanbvps,12)         |
| 0.46    | 1.22   | ts_zscore(fnd17_ttmtaxpd,12)         |
| 0.45    | 1.21   | ts_zscore(fnd17_qtaxpd,12)           |
| 0.46    | 1.2    | ts_zscore(fnd17_alldelay1_beta,12)   |
| 0.54    | 1.18   | ts_zscore(fnd17_divnq,12)            |
| 0.43    | 1.17   | ts_zscore(fnd17_qwcappspr,12)        |
| 0.42    | 1.16   | ts_zscore(fnd17_alldelay1_tbemtt,12) |

**Analyst Revision** **model26**

| fitness | sharpe | expression                                           |
| ------- | ------ | ---------------------------------------------------- |
| 1.41    | 3.26   | ts_zscore(mdl26_blndd_grwth_rt_smrtstmt,12)          |
| 1.25    | 2.93   | ts_zscore(mdl26_ep_industry_percentile_fy1,12)       |
| 1.18    | 2.87   | ts_zscore(mdl26_yld_ndstry_prcntl_fy1_rnngs,12)      |
| 1.27    | 2.84   | ts_zscore(mdl26_smrtst_grwth_ths_yrlst_yr_rnngs,12)  |
| 1.27    | 2.77   | ts_zscore(mdl26_yld_sctr_prcntl_fy1_rnngs,12)        |
| 1.5     | 2.72   | ts_zscore(mdl26_ep_yield_smartestimate_fy1,12)       |
| 1.28    | 2.71   | ts_zscore(mdl26_ep_sector_percentile_fy1,12)         |
| 1.5     | 2.7    | ts_zscore(mdl26_yld_stm_fy1_rnngs,12)                |
| 0.76    | 2.47   | ts_zscore(star_arm_score_change_1m,12)               |
| 0.8     | 2.38   | ts_zscore(star_arm_global_rank,12)                   |
| 1.46    | 2.19   | ts_zscore(mdl26_surprise_last_q_earnings,12)         |
| 0.7     | 2.17   | ts_zscore(star_arm_region_rank_decimal,12)           |
| 0.68    | 2.16   | ts_zscore(star_arm_score,12)                         |
| 0.65    | 2.05   | ts_zscore(star_arm_secondary_earnings_score,12)      |
| 0.63    | 1.99   | ts_zscore(star_arm_pref_earnings_score,12)           |
| 1.15    | 1.95   | ts_zscore(mdl26_actual_last_q_earnings,12)           |
| 0.52    | 1.75   | ts_zscore(star_arm_revenue_score,12)                 |
| 0.93    | 1.62   | ts_zscore(mdl26_60dy_srprs_lst_q_rnngs,12)           |
| 0.43    | 1.61   | ts_zscore(star_arm_country_rank,12)                  |
| 0.53    | 1.42   | ts_zscore(mdl26_smartestimate_fq1_earnings,12)       |
| 0.36    | 1.31   | ts_zscore(mdl26_blndd_grwth_sctr_prcntl,12)          |
| 0.45    | 1.27   | ts_zscore(mdl26_stm_prr_fq1_rnngs_7,12)              |
| 0.62    | 1.27   | ts_zscore(star_arm_rec_days_since_newsell,12)        |
| 0.39    | 1.26   | ts_zscore(mdl26_grwth_ths_yr_sctr_prcntl_rnngs,12)-1 |

| -1    | -1.99 | ts_zscore(mdl26_chng_frm_52wk_hgh_prc,12)          |
| ----- | ----- | -------------------------------------------------- |
| -1.13 | -1.99 | ts_zscore(mdl26_trailing_4_quarter_pe,12)          |
| -1.28 | -2.36 | ts_zscore(mdl26_mn_stmt_prc_rt_fy1_rnngs,12)       |
| -1.29 | -2.38 | ts_zscore(mdl26_forward_pe_mean_fy1,12)            |
| -1.3  | -2.39 | ts_zscore(mdl26_dffrnc_frm_hstrcl_prc_rt_rnngs,12) |
| -1.31 | -2.4  | ts_zscore(mdl26_dffrnc_frm_hstrcl_p,12)            |
| -1.48 | -2.63 | ts_zscore(mdl26_frwrd_p_stm_fy1,12)                |
| -1.49 | -2.63 | ts_zscore(mdl26_stm_prc_rt_fy1_rnngs,12)           |
| -1.59 | -2.85 | ts_zscore(mdl26_peg_mean_fy1,12)                   |
| -1.37 | -3.03 | ts_zscore(mdl26_smrtst_pg_sctr_prcntl_f12m,12)     |
| -1.81 | -3.16 | ts_zscore(mdl26_peg_smartestimate_fy1,12)          |
| -1.28 | -3.21 | ts_zscore(mdl26_smrtst_pg_ndstry_prcntl_f12m,12)   |
| -1.41 | -3.44 | ts_zscore(star_arm_score_5,12)                     |

**model30**

| fitness | sharpe | expression                                     |
| ------- | ------ | ---------------------------------------------- |
| 1.42    | 2.82   | ts_zscore(star_eps_smart_estimate_fy2,12)      |
| 1.23    | 3.06   | ts_zscore(star_eps_surprise_prediction_12m,12) |
| 1.21    | 3.01   | ts_zscore(star_eps_surprise_prediction_fy2,12) |
| 1       | 2.61   | ts_zscore(star_eps_surprise_prediction_fy1,12) |
| 0.94    | 2.06   | ts_zscore(star_eps_smart_estimate_12m,12)      |
| 0.83    | 1.96   | ts_zscore(star_eps_smart_estimate_fy1,12)      |