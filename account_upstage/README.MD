只显示末级科目：
    * hr.expense 科目(account_id)
    * account.invoice 客户发票行的科目(account_id)
                        客户发票的科目(account_id)
                        供应商账单行的科目(account_id)
    * account.move 日记账分录上面的科目(account_id)
    * res.partner 客户里面的应收账款(property_account_receivable_id)
                            应付账款(property_account_payable_id)
    * product.template 产品里面的 收入科目(property_account_income_id)
                                费用科目(property_account_expense_id)
                                价格差异科目(property_account_creditor_price_difference)
    * product.category 产品类别的库存进货科目(property_stock_account_input_categ_id)、
                                库存出货科目(property_stock_account_output_categ_id)
                                库存计价科目(property_stock_valuation_account_id)
                                收入科目(property_account_income_categ_id)
                                费用科目(property_account_expense_categ_id)
                                价格差异科目(property_account_creditor_price_difference_categ)
    * account.asset.category 资产类型 资产科目(account_asset_id)
                                    折旧分录: 资产科目(account_depreciation_id)
                                    折旧分录: 费用科目(account_depreciation_expense_id)

2018.05.08
    * 更新日记账项目里面的科目，显示最末级

2018.05.10
    * 更新设置-日记账，里面的默认借方科目、默认贷方科目、允许的科目 只显示末级