make_cxxtest(space_saving_test.cxx REQUIRES sketches random flexible_type)
make_cxxtest(hyperloglog_test.cxx REQUIRES sketches random)
make_cxxtest(quantile_test.cxx REQUIRES sketches random)
make_cxxtest(count_sketches_test.cxx REQUIRES sketches random timer)
