Output of report.txt:

Flat profile:

Each sample counts as 0.01 seconds.
 no time accumulated

  %   cumulative   self              self     total           
 time   seconds   seconds    calls  Ts/call  Ts/call  name    
  0.00      0.00     0.00       38     0.00     0.00  std::vector<int, std::allocator<int> >::operator[](unsigned long)
  0.00      0.00     0.00       27     0.00     0.00  std::remove_reference<int&>::type&& std::move<int&>(int&)
  0.00      0.00     0.00       24     0.00     0.00  __gnu_cxx::__normal_iterator<int const*, std::vector<int, std::allocator<int> > >::base() const
  0.00      0.00     0.00       12     0.00     0.00  bool __gnu_cxx::operator!=<int const*, std::vector<int, std::allocator<int> > >(__gnu_cxx::__normal_iterator<int const*, std::vector<int, std::allocator<int> > > const&, __gnu_cxx::__normal_iterator<int const*, std::vector<int, std::allocator<int> > > const&)
  0.00      0.00     0.00       10     0.00     0.00  __gnu_cxx::__normal_iterator<int const*, std::vector<int, std::allocator<int> > >::operator++()
  0.00      0.00     0.00       10     0.00     0.00  __gnu_cxx::__normal_iterator<int const*, std::vector<int, std::allocator<int> > >::operator*() const
  0.00      0.00     0.00        9     0.00     0.00  std::enable_if<std::__and_<std::__not_<std::__is_tuple_like<int> >, std::is_move_constructible<int>, std::is_move_assignable<int> >::value, void>::type std::swap<int>(int&, int&)
  0.00      0.00     0.00        4     0.00     0.00  __gnu_cxx::__normal_iterator<int const*, std::vector<int, std::allocator<int> > >::__normal_iterator(int const* const&)
  0.00      0.00     0.00        3     0.00     0.00  std::allocator<int>::~allocator()
  0.00      0.00     0.00        3     0.00     0.00  std::_Vector_base<int, std::allocator<int> >::_M_get_Tp_allocator()
  0.00      0.00     0.00        3     0.00     0.00  std::__new_allocator<int>::~__new_allocator()
  0.00      0.00     0.00        2     0.00     0.00  printArray(std::vector<int, std::allocator<int> > const&)
  0.00      0.00     0.00        2     0.00     0.00  std::__new_allocator<int>::_M_max_size() const
  0.00      0.00     0.00        2     0.00     0.00  std::initializer_list<int>::begin() const
  0.00      0.00     0.00        2     0.00     0.00  std::vector<int, std::allocator<int> >::end() const
  0.00      0.00     0.00        2     0.00     0.00  std::vector<int, std::allocator<int> >::begin() const
  0.00      0.00     0.00        2     0.00     0.00  std::allocator<int>::allocator(std::allocator<int> const&)
  0.00      0.00     0.00        2     0.00     0.00  std::__new_allocator<int>::__new_allocator(std::__new_allocator<int> const&)
  0.00      0.00     0.00        2     0.00     0.00  int const* std::__miter_base<int const*>(int const*)
  0.00      0.00     0.00        2     0.00     0.00  int const* std::__niter_base<int const*>(int const*)
  0.00      0.00     0.00        1     0.00     0.00  bubbleSort(std::vector<int, std::allocator<int> >&)
  0.00      0.00     0.00        1     0.00     0.00  __static_initialization_and_destruction_0(int, int)
  0.00      0.00     0.00        1     0.00     0.00  std::__new_allocator<int>::max_size() const
  0.00      0.00     0.00        1     0.00     0.00  std::initializer_list<int>::end() const
  0.00      0.00     0.00        1     0.00     0.00  std::initializer_list<int>::size() const
  0.00      0.00     0.00        1     0.00     0.00  std::vector<int, std::allocator<int> >::size() const
  0.00      0.00     0.00        1     0.00     0.00  std::allocator<int>::allocator()
  0.00      0.00     0.00        1     0.00     0.00  int* std::__copy_move<false, true, std::random_access_iterator_tag>::__copy_m<int>(int const*, int const*, int*)
  0.00      0.00     0.00        1     0.00     0.00  void std::_Destroy_aux<true>::__destroy<int*>(int*, int*)
  0.00      0.00     0.00        1     0.00     0.00  std::_Vector_base<int, std::allocator<int> >::_M_allocate(unsigned long)
  0.00      0.00     0.00        1     0.00     0.00  std::_Vector_base<int, std::allocator<int> >::_Vector_impl::_Vector_impl(std::allocator<int> const&)
  0.00      0.00     0.00        1     0.00     0.00  std::_Vector_base<int, std::allocator<int> >::_Vector_impl::~_Vector_impl()
  0.00      0.00     0.00        1     0.00     0.00  std::_Vector_base<int, std::allocator<int> >::_M_deallocate(int*, unsigned long)
  0.00      0.00     0.00        1     0.00     0.00  std::_Vector_base<int, std::allocator<int> >::_Vector_impl_data::_Vector_impl_data()
  0.00      0.00     0.00        1     0.00     0.00  std::_Vector_base<int, std::allocator<int> >::_Vector_base(std::allocator<int> const&)
  0.00      0.00     0.00        1     0.00     0.00  std::_Vector_base<int, std::allocator<int> >::~_Vector_base()
  0.00      0.00     0.00        1     0.00     0.00  std::__new_allocator<int>::deallocate(int*, unsigned long)
  0.00      0.00     0.00        1     0.00     0.00  std::__new_allocator<int>::allocate(unsigned long, void const*)
  0.00      0.00     0.00        1     0.00     0.00  std::__new_allocator<int>::__new_allocator()
  0.00      0.00     0.00        1     0.00     0.00  std::allocator_traits<std::allocator<int> >::deallocate(std::allocator<int>&, int*, unsigned long)
  0.00      0.00     0.00        1     0.00     0.00  std::allocator_traits<std::allocator<int> >::allocate(std::allocator<int>&, unsigned long)
  0.00      0.00     0.00        1     0.00     0.00  std::allocator_traits<std::allocator<int> >::max_size(std::allocator<int> const&)
  0.00      0.00     0.00        1     0.00     0.00  int* std::__uninitialized_copy<true>::__uninit_copy<int const*, int*>(int const*, int const*, int*)
  0.00      0.00     0.00        1     0.00     0.00  std::vector<int, std::allocator<int> >::_S_max_size(std::allocator<int> const&)
  0.00      0.00     0.00        1     0.00     0.00  std::vector<int, std::allocator<int> >::_S_check_init_len(unsigned long, std::allocator<int> const&)
  0.00      0.00     0.00        1     0.00     0.00  void std::vector<int, std::allocator<int> >::_M_range_initialize<int const*>(int const*, int const*, std::forward_iterator_tag)
  0.00      0.00     0.00        1     0.00     0.00  std::vector<int, std::allocator<int> >::vector(std::initializer_list<int>, std::allocator<int> const&)
  0.00      0.00     0.00        1     0.00     0.00  std::vector<int, std::allocator<int> >::~vector()
  0.00      0.00     0.00        1     0.00     0.00  std::iterator_traits<int const*>::difference_type std::__distance<int const*>(int const*, int const*, std::random_access_iterator_tag)
  0.00      0.00     0.00        1     0.00     0.00  int* std::__niter_base<int*>(int*)
  0.00      0.00     0.00        1     0.00     0.00  int* std::__niter_wrap<int*>(int* const&, int*)
  0.00      0.00     0.00        1     0.00     0.00  int* std::__copy_move_a<false, int const*, int*>(int const*, int const*, int*)
  0.00      0.00     0.00        1     0.00     0.00  int* std::__copy_move_a1<false, int const*, int*>(int const*, int const*, int*)
  0.00      0.00     0.00        1     0.00     0.00  int* std::__copy_move_a2<false, int const*, int*>(int const*, int const*, int*)
  0.00      0.00     0.00        1     0.00     0.00  int* std::uninitialized_copy<int const*, int*>(int const*, int const*, int*)
  0.00      0.00     0.00        1     0.00     0.00  std::iterator_traits<int const*>::iterator_category std::__iterator_category<int const*>(int const* const&)
  0.00      0.00     0.00        1     0.00     0.00  int* std::__uninitialized_copy_a<int const*, int*, int>(int const*, int const*, int*, std::allocator<int>&)
  0.00      0.00     0.00        1     0.00     0.00  unsigned long const& std::min<unsigned long>(unsigned long const&, unsigned long const&)
  0.00      0.00     0.00        1     0.00     0.00  int* std::copy<int const*, int*>(int const*, int const*, int*)
  0.00      0.00     0.00        1     0.00     0.00  void std::_Destroy<int*>(int*, int*)
  0.00      0.00     0.00        1     0.00     0.00  void std::_Destroy<int*, int>(int*, int*, std::allocator<int>&)
  0.00      0.00     0.00        1     0.00     0.00  std::iterator_traits<int const*>::difference_type std::distance<int const*>(int const*, int const*)

 %         the percentage of the total running time of the
time       program used by this function.

cumulative a running sum of the number of seconds accounted
 seconds   for by this function and those listed above it.

 self      the number of seconds accounted for by this
seconds    function alone.  This is the major sort for this
           listing.

calls      the number of times this function was invoked, if
           this function is profiled, else blank.

 self      the average number of milliseconds spent in this
ms/call    function per call, if this function is profiled,
	   else blank.

 total     the average number of milliseconds spent in this
ms/call    function and its descendents per call, if this
	   function is profiled, else blank.

name       the name of the function.  This is the minor sort
           for this listing. The index shows the location of
	   the function in the gprof listing. If the index is
	   in parenthesis it shows where it would appear in
	   the gprof listing if it were to be printed.

Copyright (C) 2012-2023 Free Software Foundation, Inc.

Copying and distribution of this file, with or without modification,
are permitted in any medium without royalty provided the copyright
notice and this notice are preserved.

		     Call graph (explanation follows)


granularity: each sample hit covers 4 byte(s) no time propagated

index % time    self  children    called     name
                0.00    0.00      38/38          bubbleSort(std::vector<int, std::allocator<int> >&) [28]
[8]      0.0    0.00    0.00      38         std::vector<int, std::allocator<int> >::operator[](unsigned long) [8]
-----------------------------------------------
                0.00    0.00      27/27          std::enable_if<std::__and_<std::__not_<std::__is_tuple_like<int> >, std::is_move_constructible<int>, std::is_move_assignable<int> >::value, void>::type std::swap<int>(int&, int&) [14]
[9]      0.0    0.00    0.00      27         std::remove_reference<int&>::type&& std::move<int&>(int&) [9]
-----------------------------------------------
                0.00    0.00      24/24          bool __gnu_cxx::operator!=<int const*, std::vector<int, std::allocator<int> > >(__gnu_cxx::__normal_iterator<int const*, std::vector<int, std::allocator<int> > > const&, __gnu_cxx::__normal_iterator<int const*, std::vector<int, std::allocator<int> > > const&) [11]
[10]     0.0    0.00    0.00      24         __gnu_cxx::__normal_iterator<int const*, std::vector<int, std::allocator<int> > >::base() const [10]
-----------------------------------------------
                0.00    0.00      12/12          printArray(std::vector<int, std::allocator<int> > const&) [19]
[11]     0.0    0.00    0.00      12         bool __gnu_cxx::operator!=<int const*, std::vector<int, std::allocator<int> > >(__gnu_cxx::__normal_iterator<int const*, std::vector<int, std::allocator<int> > > const&, __gnu_cxx::__normal_iterator<int const*, std::vector<int, std::allocator<int> > > const&) [11]
                0.00    0.00      24/24          __gnu_cxx::__normal_iterator<int const*, std::vector<int, std::allocator<int> > >::base() const [10]
-----------------------------------------------
                0.00    0.00      10/10          printArray(std::vector<int, std::allocator<int> > const&) [19]
[12]     0.0    0.00    0.00      10         __gnu_cxx::__normal_iterator<int const*, std::vector<int, std::allocator<int> > >::operator++() [12]
-----------------------------------------------
                0.00    0.00      10/10          printArray(std::vector<int, std::allocator<int> > const&) [19]
[13]     0.0    0.00    0.00      10         __gnu_cxx::__normal_iterator<int const*, std::vector<int, std::allocator<int> > >::operator*() const [13]
-----------------------------------------------
                0.00    0.00       9/9           bubbleSort(std::vector<int, std::allocator<int> >&) [28]
[14]     0.0    0.00    0.00       9         std::enable_if<std::__and_<std::__not_<std::__is_tuple_like<int> >, std::is_move_constructible<int>, std::is_move_assignable<int> >::value, void>::type std::swap<int>(int&, int&) [14]
                0.00    0.00      27/27          std::remove_reference<int&>::type&& std::move<int&>(int&) [9]
-----------------------------------------------
                0.00    0.00       2/4           std::vector<int, std::allocator<int> >::begin() const [23]
                0.00    0.00       2/4           std::vector<int, std::allocator<int> >::end() const [22]
[15]     0.0    0.00    0.00       4         __gnu_cxx::__normal_iterator<int const*, std::vector<int, std::allocator<int> > >::__normal_iterator(int const* const&) [15]
-----------------------------------------------
                0.00    0.00       1/3           main [6]
                0.00    0.00       1/3           std::_Vector_base<int, std::allocator<int> >::_Vector_impl::~_Vector_impl() [39]
                0.00    0.00       1/3           std::vector<int, std::allocator<int> >::_S_check_init_len(unsigned long, std::allocator<int> const&) [52]
[16]     0.0    0.00    0.00       3         std::allocator<int>::~allocator() [16]
                0.00    0.00       3/3           std::__new_allocator<int>::~__new_allocator() [18]
-----------------------------------------------
                0.00    0.00       1/3           std::vector<int, std::allocator<int> >::~vector() [55]
                0.00    0.00       2/3           void std::vector<int, std::allocator<int> >::_M_range_initialize<int const*>(int const*, int const*, std::forward_iterator_tag) [53]
[17]     0.0    0.00    0.00       3         std::_Vector_base<int, std::allocator<int> >::_M_get_Tp_allocator() [17]
-----------------------------------------------
                0.00    0.00       3/3           std::allocator<int>::~allocator() [16]
[18]     0.0    0.00    0.00       3         std::__new_allocator<int>::~__new_allocator() [18]
-----------------------------------------------
                0.00    0.00       2/2           main [6]
[19]     0.0    0.00    0.00       2         printArray(std::vector<int, std::allocator<int> > const&) [19]
                0.00    0.00      12/12          bool __gnu_cxx::operator!=<int const*, std::vector<int, std::allocator<int> > >(__gnu_cxx::__normal_iterator<int const*, std::vector<int, std::allocator<int> > > const&, __gnu_cxx::__normal_iterator<int const*, std::vector<int, std::allocator<int> > > const&) [11]
                0.00    0.00      10/10          __gnu_cxx::__normal_iterator<int const*, std::vector<int, std::allocator<int> > >::operator*() const [13]
                0.00    0.00      10/10          __gnu_cxx::__normal_iterator<int const*, std::vector<int, std::allocator<int> > >::operator++() [12]
                0.00    0.00       2/2           std::vector<int, std::allocator<int> >::begin() const [23]
                0.00    0.00       2/2           std::vector<int, std::allocator<int> >::end() const [22]
-----------------------------------------------
                0.00    0.00       1/2           std::__new_allocator<int>::allocate(unsigned long, void const*) [45]
                0.00    0.00       1/2           std::__new_allocator<int>::max_size() const [30]
[20]     0.0    0.00    0.00       2         std::__new_allocator<int>::_M_max_size() const [20]
-----------------------------------------------
                0.00    0.00       1/2           std::vector<int, std::allocator<int> >::vector(std::initializer_list<int>, std::allocator<int> const&) [54]
                0.00    0.00       1/2           std::initializer_list<int>::end() const [31]
[21]     0.0    0.00    0.00       2         std::initializer_list<int>::begin() const [21]
-----------------------------------------------
                0.00    0.00       2/2           printArray(std::vector<int, std::allocator<int> > const&) [19]
[22]     0.0    0.00    0.00       2         std::vector<int, std::allocator<int> >::end() const [22]
                0.00    0.00       2/4           __gnu_cxx::__normal_iterator<int const*, std::vector<int, std::allocator<int> > >::__normal_iterator(int const* const&) [15]
-----------------------------------------------
                0.00    0.00       2/2           printArray(std::vector<int, std::allocator<int> > const&) [19]
[23]     0.0    0.00    0.00       2         std::vector<int, std::allocator<int> >::begin() const [23]
                0.00    0.00       2/4           __gnu_cxx::__normal_iterator<int const*, std::vector<int, std::allocator<int> > >::__normal_iterator(int const* const&) [15]
-----------------------------------------------
                0.00    0.00       1/2           std::_Vector_base<int, std::allocator<int> >::_Vector_impl::_Vector_impl(std::allocator<int> const&) [38]
                0.00    0.00       1/2           std::vector<int, std::allocator<int> >::_S_check_init_len(unsigned long, std::allocator<int> const&) [52]
[24]     0.0    0.00    0.00       2         std::allocator<int>::allocator(std::allocator<int> const&) [24]
                0.00    0.00       2/2           std::__new_allocator<int>::__new_allocator(std::__new_allocator<int> const&) [25]
-----------------------------------------------
                0.00    0.00       2/2           std::allocator<int>::allocator(std::allocator<int> const&) [24]
[25]     0.0    0.00    0.00       2         std::__new_allocator<int>::__new_allocator(std::__new_allocator<int> const&) [25]
-----------------------------------------------
                0.00    0.00       2/2           int* std::copy<int const*, int*>(int const*, int const*, int*) [66]
[26]     0.0    0.00    0.00       2         int const* std::__miter_base<int const*>(int const*) [26]
-----------------------------------------------
                0.00    0.00       2/2           int* std::__copy_move_a<false, int const*, int*>(int const*, int const*, int*) [59]
[27]     0.0    0.00    0.00       2         int const* std::__niter_base<int const*>(int const*) [27]
-----------------------------------------------
                0.00    0.00       1/1           main [6]
[28]     0.0    0.00    0.00       1         bubbleSort(std::vector<int, std::allocator<int> >&) [28]
                0.00    0.00      38/38          std::vector<int, std::allocator<int> >::operator[](unsigned long) [8]
                0.00    0.00       9/9           std::enable_if<std::__and_<std::__not_<std::__is_tuple_like<int> >, std::is_move_constructible<int>, std::is_move_assignable<int> >::value, void>::type std::swap<int>(int&, int&) [14]
                0.00    0.00       1/1           std::vector<int, std::allocator<int> >::size() const [33]
-----------------------------------------------
                0.00    0.00       1/1           _GLOBAL__sub_I__Z10bubbleSortRSt6vectorIiSaIiEE [70]
[29]     0.0    0.00    0.00       1         __static_initialization_and_destruction_0(int, int) [29]
-----------------------------------------------
                0.00    0.00       1/1           std::allocator_traits<std::allocator<int> >::max_size(std::allocator<int> const&) [49]
[30]     0.0    0.00    0.00       1         std::__new_allocator<int>::max_size() const [30]
                0.00    0.00       1/2           std::__new_allocator<int>::_M_max_size() const [20]
-----------------------------------------------
                0.00    0.00       1/1           std::vector<int, std::allocator<int> >::vector(std::initializer_list<int>, std::allocator<int> const&) [54]
[31]     0.0    0.00    0.00       1         std::initializer_list<int>::end() const [31]
                0.00    0.00       1/2           std::initializer_list<int>::begin() const [21]
                0.00    0.00       1/1           std::initializer_list<int>::size() const [32]
-----------------------------------------------
                0.00    0.00       1/1           std::initializer_list<int>::end() const [31]
[32]     0.0    0.00    0.00       1         std::initializer_list<int>::size() const [32]
-----------------------------------------------
                0.00    0.00       1/1           bubbleSort(std::vector<int, std::allocator<int> >&) [28]
[33]     0.0    0.00    0.00       1         std::vector<int, std::allocator<int> >::size() const [33]
-----------------------------------------------
                0.00    0.00       1/1           main [6]
[34]     0.0    0.00    0.00       1         std::allocator<int>::allocator() [34]
                0.00    0.00       1/1           std::__new_allocator<int>::__new_allocator() [46]
-----------------------------------------------
                0.00    0.00       1/1           int* std::__copy_move_a2<false, int const*, int*>(int const*, int const*, int*) [61]
[35]     0.0    0.00    0.00       1         int* std::__copy_move<false, true, std::random_access_iterator_tag>::__copy_m<int>(int const*, int const*, int*) [35]
-----------------------------------------------
                0.00    0.00       1/1           void std::_Destroy<int*>(int*, int*) [67]
[36]     0.0    0.00    0.00       1         void std::_Destroy_aux<true>::__destroy<int*>(int*, int*) [36]
-----------------------------------------------
                0.00    0.00       1/1           void std::vector<int, std::allocator<int> >::_M_range_initialize<int const*>(int const*, int const*, std::forward_iterator_tag) [53]
[37]     0.0    0.00    0.00       1         std::_Vector_base<int, std::allocator<int> >::_M_allocate(unsigned long) [37]
                0.00    0.00       1/1           std::allocator_traits<std::allocator<int> >::allocate(std::allocator<int>&, unsigned long) [48]
-----------------------------------------------
                0.00    0.00       1/1           std::_Vector_base<int, std::allocator<int> >::_Vector_base(std::allocator<int> const&) [42]
[38]     0.0    0.00    0.00       1         std::_Vector_base<int, std::allocator<int> >::_Vector_impl::_Vector_impl(std::allocator<int> const&) [38]
                0.00    0.00       1/2           std::allocator<int>::allocator(std::allocator<int> const&) [24]
                0.00    0.00       1/1           std::_Vector_base<int, std::allocator<int> >::_Vector_impl_data::_Vector_impl_data() [41]
-----------------------------------------------
                0.00    0.00       1/1           std::_Vector_base<int, std::allocator<int> >::~_Vector_base() [43]
[39]     0.0    0.00    0.00       1         std::_Vector_base<int, std::allocator<int> >::_Vector_impl::~_Vector_impl() [39]
                0.00    0.00       1/3           std::allocator<int>::~allocator() [16]
-----------------------------------------------
                0.00    0.00       1/1           std::_Vector_base<int, std::allocator<int> >::~_Vector_base() [43]
[40]     0.0    0.00    0.00       1         std::_Vector_base<int, std::allocator<int> >::_M_deallocate(int*, unsigned long) [40]
                0.00    0.00       1/1           std::allocator_traits<std::allocator<int> >::deallocate(std::allocator<int>&, int*, unsigned long) [47]
-----------------------------------------------
                0.00    0.00       1/1           std::_Vector_base<int, std::allocator<int> >::_Vector_impl::_Vector_impl(std::allocator<int> const&) [38]
[41]     0.0    0.00    0.00       1         std::_Vector_base<int, std::allocator<int> >::_Vector_impl_data::_Vector_impl_data() [41]
-----------------------------------------------
                0.00    0.00       1/1           std::vector<int, std::allocator<int> >::vector(std::initializer_list<int>, std::allocator<int> const&) [54]
[42]     0.0    0.00    0.00       1         std::_Vector_base<int, std::allocator<int> >::_Vector_base(std::allocator<int> const&) [42]
                0.00    0.00       1/1           std::_Vector_base<int, std::allocator<int> >::_Vector_impl::_Vector_impl(std::allocator<int> const&) [38]
-----------------------------------------------
                0.00    0.00       1/1           std::vector<int, std::allocator<int> >::~vector() [55]
[43]     0.0    0.00    0.00       1         std::_Vector_base<int, std::allocator<int> >::~_Vector_base() [43]
                0.00    0.00       1/1           std::_Vector_base<int, std::allocator<int> >::_M_deallocate(int*, unsigned long) [40]
                0.00    0.00       1/1           std::_Vector_base<int, std::allocator<int> >::_Vector_impl::~_Vector_impl() [39]
-----------------------------------------------
                0.00    0.00       1/1           std::allocator_traits<std::allocator<int> >::deallocate(std::allocator<int>&, int*, unsigned long) [47]
[44]     0.0    0.00    0.00       1         std::__new_allocator<int>::deallocate(int*, unsigned long) [44]
-----------------------------------------------
                0.00    0.00       1/1           std::allocator_traits<std::allocator<int> >::allocate(std::allocator<int>&, unsigned long) [48]
[45]     0.0    0.00    0.00       1         std::__new_allocator<int>::allocate(unsigned long, void const*) [45]
                0.00    0.00       1/2           std::__new_allocator<int>::_M_max_size() const [20]
-----------------------------------------------
                0.00    0.00       1/1           std::allocator<int>::allocator() [34]
[46]     0.0    0.00    0.00       1         std::__new_allocator<int>::__new_allocator() [46]
-----------------------------------------------
                0.00    0.00       1/1           std::_Vector_base<int, std::allocator<int> >::_M_deallocate(int*, unsigned long) [40]
[47]     0.0    0.00    0.00       1         std::allocator_traits<std::allocator<int> >::deallocate(std::allocator<int>&, int*, unsigned long) [47]
                0.00    0.00       1/1           std::__new_allocator<int>::deallocate(int*, unsigned long) [44]
-----------------------------------------------
                0.00    0.00       1/1           std::_Vector_base<int, std::allocator<int> >::_M_allocate(unsigned long) [37]
[48]     0.0    0.00    0.00       1         std::allocator_traits<std::allocator<int> >::allocate(std::allocator<int>&, unsigned long) [48]
                0.00    0.00       1/1           std::__new_allocator<int>::allocate(unsigned long, void const*) [45]
-----------------------------------------------
                0.00    0.00       1/1           std::vector<int, std::allocator<int> >::_S_max_size(std::allocator<int> const&) [51]
[49]     0.0    0.00    0.00       1         std::allocator_traits<std::allocator<int> >::max_size(std::allocator<int> const&) [49]
                0.00    0.00       1/1           std::__new_allocator<int>::max_size() const [30]
-----------------------------------------------
                0.00    0.00       1/1           int* std::uninitialized_copy<int const*, int*>(int const*, int const*, int*) [62]
[50]     0.0    0.00    0.00       1         int* std::__uninitialized_copy<true>::__uninit_copy<int const*, int*>(int const*, int const*, int*) [50]
                0.00    0.00       1/1           int* std::copy<int const*, int*>(int const*, int const*, int*) [66]
-----------------------------------------------
                0.00    0.00       1/1           std::vector<int, std::allocator<int> >::_S_check_init_len(unsigned long, std::allocator<int> const&) [52]
[51]     0.0    0.00    0.00       1         std::vector<int, std::allocator<int> >::_S_max_size(std::allocator<int> const&) [51]
                0.00    0.00       1/1           std::allocator_traits<std::allocator<int> >::max_size(std::allocator<int> const&) [49]
                0.00    0.00       1/1           unsigned long const& std::min<unsigned long>(unsigned long const&, unsigned long const&) [65]
-----------------------------------------------
                0.00    0.00       1/1           void std::vector<int, std::allocator<int> >::_M_range_initialize<int const*>(int const*, int const*, std::forward_iterator_tag) [53]
[52]     0.0    0.00    0.00       1         std::vector<int, std::allocator<int> >::_S_check_init_len(unsigned long, std::allocator<int> const&) [52]
                0.00    0.00       1/2           std::allocator<int>::allocator(std::allocator<int> const&) [24]
                0.00    0.00       1/1           std::vector<int, std::allocator<int> >::_S_max_size(std::allocator<int> const&) [51]
                0.00    0.00       1/3           std::allocator<int>::~allocator() [16]
-----------------------------------------------
                0.00    0.00       1/1           std::vector<int, std::allocator<int> >::vector(std::initializer_list<int>, std::allocator<int> const&) [54]
[53]     0.0    0.00    0.00       1         void std::vector<int, std::allocator<int> >::_M_range_initialize<int const*>(int const*, int const*, std::forward_iterator_tag) [53]
                0.00    0.00       2/3           std::_Vector_base<int, std::allocator<int> >::_M_get_Tp_allocator() [17]
                0.00    0.00       1/1           std::iterator_traits<int const*>::difference_type std::distance<int const*>(int const*, int const*) [69]
                0.00    0.00       1/1           std::_Vector_base<int, std::allocator<int> >::_M_allocate(unsigned long) [37]
                0.00    0.00       1/1           std::vector<int, std::allocator<int> >::_S_check_init_len(unsigned long, std::allocator<int> const&) [52]
                0.00    0.00       1/1           int* std::__uninitialized_copy_a<int const*, int*, int>(int const*, int const*, int*, std::allocator<int>&) [64]
-----------------------------------------------
                0.00    0.00       1/1           main [6]
[54]     0.0    0.00    0.00       1         std::vector<int, std::allocator<int> >::vector(std::initializer_list<int>, std::allocator<int> const&) [54]
                0.00    0.00       1/1           std::initializer_list<int>::end() const [31]
                0.00    0.00       1/1           std::_Vector_base<int, std::allocator<int> >::_Vector_base(std::allocator<int> const&) [42]
                0.00    0.00       1/2           std::initializer_list<int>::begin() const [21]
                0.00    0.00       1/1           void std::vector<int, std::allocator<int> >::_M_range_initialize<int const*>(int const*, int const*, std::forward_iterator_tag) [53]
-----------------------------------------------
                0.00    0.00       1/1           main [6]
[55]     0.0    0.00    0.00       1         std::vector<int, std::allocator<int> >::~vector() [55]
                0.00    0.00       1/3           std::_Vector_base<int, std::allocator<int> >::_M_get_Tp_allocator() [17]
                0.00    0.00       1/1           void std::_Destroy<int*, int>(int*, int*, std::allocator<int>&) [68]
                0.00    0.00       1/1           std::_Vector_base<int, std::allocator<int> >::~_Vector_base() [43]
-----------------------------------------------
                0.00    0.00       1/1           std::iterator_traits<int const*>::difference_type std::distance<int const*>(int const*, int const*) [69]
[56]     0.0    0.00    0.00       1         std::iterator_traits<int const*>::difference_type std::__distance<int const*>(int const*, int const*, std::random_access_iterator_tag) [56]
-----------------------------------------------
                0.00    0.00       1/1           int* std::__copy_move_a<false, int const*, int*>(int const*, int const*, int*) [59]
[57]     0.0    0.00    0.00       1         int* std::__niter_base<int*>(int*) [57]
-----------------------------------------------
                0.00    0.00       1/1           int* std::__copy_move_a<false, int const*, int*>(int const*, int const*, int*) [59]
[58]     0.0    0.00    0.00       1         int* std::__niter_wrap<int*>(int* const&, int*) [58]
-----------------------------------------------
                0.00    0.00       1/1           int* std::copy<int const*, int*>(int const*, int const*, int*) [66]
[59]     0.0    0.00    0.00       1         int* std::__copy_move_a<false, int const*, int*>(int const*, int const*, int*) [59]
                0.00    0.00       2/2           int const* std::__niter_base<int const*>(int const*) [27]
                0.00    0.00       1/1           int* std::__niter_base<int*>(int*) [57]
                0.00    0.00       1/1           int* std::__copy_move_a1<false, int const*, int*>(int const*, int const*, int*) [60]
                0.00    0.00       1/1           int* std::__niter_wrap<int*>(int* const&, int*) [58]
-----------------------------------------------
                0.00    0.00       1/1           int* std::__copy_move_a<false, int const*, int*>(int const*, int const*, int*) [59]
[60]     0.0    0.00    0.00       1         int* std::__copy_move_a1<false, int const*, int*>(int const*, int const*, int*) [60]
                0.00    0.00       1/1           int* std::__copy_move_a2<false, int const*, int*>(int const*, int const*, int*) [61]
-----------------------------------------------
                0.00    0.00       1/1           int* std::__copy_move_a1<false, int const*, int*>(int const*, int const*, int*) [60]
[61]     0.0    0.00    0.00       1         int* std::__copy_move_a2<false, int const*, int*>(int const*, int const*, int*) [61]
                0.00    0.00       1/1           int* std::__copy_move<false, true, std::random_access_iterator_tag>::__copy_m<int>(int const*, int const*, int*) [35]
-----------------------------------------------
                0.00    0.00       1/1           int* std::__uninitialized_copy_a<int const*, int*, int>(int const*, int const*, int*, std::allocator<int>&) [64]
[62]     0.0    0.00    0.00       1         int* std::uninitialized_copy<int const*, int*>(int const*, int const*, int*) [62]
                0.00    0.00       1/1           int* std::__uninitialized_copy<true>::__uninit_copy<int const*, int*>(int const*, int const*, int*) [50]
-----------------------------------------------
                0.00    0.00       1/1           std::iterator_traits<int const*>::difference_type std::distance<int const*>(int const*, int const*) [69]
[63]     0.0    0.00    0.00       1         std::iterator_traits<int const*>::iterator_category std::__iterator_category<int const*>(int const* const&) [63]
-----------------------------------------------
                0.00    0.00       1/1           void std::vector<int, std::allocator<int> >::_M_range_initialize<int const*>(int const*, int const*, std::forward_iterator_tag) [53]
[64]     0.0    0.00    0.00       1         int* std::__uninitialized_copy_a<int const*, int*, int>(int const*, int const*, int*, std::allocator<int>&) [64]
                0.00    0.00       1/1           int* std::uninitialized_copy<int const*, int*>(int const*, int const*, int*) [62]
-----------------------------------------------
                0.00    0.00       1/1           std::vector<int, std::allocator<int> >::_S_max_size(std::allocator<int> const&) [51]
[65]     0.0    0.00    0.00       1         unsigned long const& std::min<unsigned long>(unsigned long const&, unsigned long const&) [65]
-----------------------------------------------
                0.00    0.00       1/1           int* std::__uninitialized_copy<true>::__uninit_copy<int const*, int*>(int const*, int const*, int*) [50]
[66]     0.0    0.00    0.00       1         int* std::copy<int const*, int*>(int const*, int const*, int*) [66]
                0.00    0.00       2/2           int const* std::__miter_base<int const*>(int const*) [26]
                0.00    0.00       1/1           int* std::__copy_move_a<false, int const*, int*>(int const*, int const*, int*) [59]
-----------------------------------------------
                0.00    0.00       1/1           void std::_Destroy<int*, int>(int*, int*, std::allocator<int>&) [68]
[67]     0.0    0.00    0.00       1         void std::_Destroy<int*>(int*, int*) [67]
                0.00    0.00       1/1           void std::_Destroy_aux<true>::__destroy<int*>(int*, int*) [36]
-----------------------------------------------
                0.00    0.00       1/1           std::vector<int, std::allocator<int> >::~vector() [55]
[68]     0.0    0.00    0.00       1         void std::_Destroy<int*, int>(int*, int*, std::allocator<int>&) [68]
                0.00    0.00       1/1           void std::_Destroy<int*>(int*, int*) [67]
-----------------------------------------------
                0.00    0.00       1/1           void std::vector<int, std::allocator<int> >::_M_range_initialize<int const*>(int const*, int const*, std::forward_iterator_tag) [53]
[69]     0.0    0.00    0.00       1         std::iterator_traits<int const*>::difference_type std::distance<int const*>(int const*, int const*) [69]
                0.00    0.00       1/1           std::iterator_traits<int const*>::iterator_category std::__iterator_category<int const*>(int const* const&) [63]
                0.00    0.00       1/1           std::iterator_traits<int const*>::difference_type std::__distance<int const*>(int const*, int const*, std::random_access_iterator_tag) [56]
-----------------------------------------------

 This table describes the call tree of the program, and was sorted by
 the total amount of time spent in each function and its children.

 Each entry in this table consists of several lines.  The line with the
 index number at the left hand margin lists the current function.
 The lines above it list the functions that called this function,
 and the lines below it list the functions this one called.
 This line lists:
     index	A unique number given to each element of the table.
		Index numbers are sorted numerically.
		The index number is printed next to every function name so
		it is easier to look up where the function is in the table.

     % time	This is the percentage of the `total' time that was spent
		in this function and its children.  Note that due to
		different viewpoints, functions excluded by options, etc,
		these numbers will NOT add up to 100%.

     self	This is the total amount of time spent in this function.

     children	This is the total amount of time propagated into this
		function by its children.

     called	This is the number of times the function was called.
		If the function called itself recursively, the number
		only includes non-recursive calls, and is followed by
		a `+' and the number of recursive calls.

     name	The name of the current function.  The index number is
		printed after it.  If the function is a member of a
		cycle, the cycle number is printed between the
		function's name and the index number.


 For the function's parents, the fields have the following meanings:

     self	This is the amount of time that was propagated directly
		from the function into this parent.

     children	This is the amount of time that was propagated from
		the function's children into this parent.

     called	This is the number of times this parent called the
		function `/' the total number of times the function
		was called.  Recursive calls to the function are not
		included in the number after the `/'.

     name	This is the name of the parent.  The parent's index
		number is printed after it.  If the parent is a
		member of a cycle, the cycle number is printed between
		the name and the index number.

 If the parents of the function cannot be determined, the word
 `<spontaneous>' is printed in the `name' field, and all the other
 fields are blank.

 For the function's children, the fields have the following meanings:

     self	This is the amount of time that was propagated directly
		from the child into the function.

     children	This is the amount of time that was propagated from the
		child's children to the function.

     called	This is the number of times the function called
		this child `/' the total number of times the child
		was called.  Recursive calls by the child are not
		listed in the number after the `/'.

     name	This is the name of the child.  The child's index
		number is printed after it.  If the child is a
		member of a cycle, the cycle number is printed
		between the name and the index number.

 If there are any cycles (circles) in the call graph, there is an
 entry for the cycle-as-a-whole.  This entry shows who called the
 cycle (as parents) and the members of the cycle (as children.)
 The `+' recursive calls entry shows the number of function calls that
 were internal to the cycle, and the calls entry for each member shows,
 for that member, how many times it was called from other members of
 the cycle.

Copyright (C) 2012-2023 Free Software Foundation, Inc.

Copying and distribution of this file, with or without modification,
are permitted in any medium without royalty provided the copyright
notice and this notice are preserved.

Index by function name

  [28] bubbleSort(std::vector<int, std::allocator<int> >&) [37] std::_Vector_base<int, std::allocator<int> >::_M_allocate(unsigned long) [55] std::vector<int, std::allocator<int> >::~vector()
  [19] printArray(std::vector<int, std::allocator<int> > const&) [38] std::_Vector_base<int, std::allocator<int> >::_Vector_impl::_Vector_impl(std::allocator<int> const&) [8] std::vector<int, std::allocator<int> >::operator[](unsigned long)
  [29] __static_initialization_and_destruction_0(int, int) [39] std::_Vector_base<int, std::allocator<int> >::_Vector_impl::~_Vector_impl() [56] std::iterator_traits<int const*>::difference_type std::__distance<int const*>(int const*, int const*, std::random_access_iterator_tag)
  [15] __gnu_cxx::__normal_iterator<int const*, std::vector<int, std::allocator<int> > >::__normal_iterator(int const* const&) [40] std::_Vector_base<int, std::allocator<int> >::_M_deallocate(int*, unsigned long) [26] int const* std::__miter_base<int const*>(int const*)
  [12] __gnu_cxx::__normal_iterator<int const*, std::vector<int, std::allocator<int> > >::operator++() [41] std::_Vector_base<int, std::allocator<int> >::_Vector_impl_data::_Vector_impl_data() [27] int const* std::__niter_base<int const*>(int const*)
  [11] bool __gnu_cxx::operator!=<int const*, std::vector<int, std::allocator<int> > >(__gnu_cxx::__normal_iterator<int const*, std::vector<int, std::allocator<int> > > const&, __gnu_cxx::__normal_iterator<int const*, std::vector<int, std::allocator<int> > > const&) [17] std::_Vector_base<int, std::allocator<int> >::_M_get_Tp_allocator() [57] int* std::__niter_base<int*>(int*)
  [10] __gnu_cxx::__normal_iterator<int const*, std::vector<int, std::allocator<int> > >::base() const [42] std::_Vector_base<int, std::allocator<int> >::_Vector_base(std::allocator<int> const&) [58] int* std::__niter_wrap<int*>(int* const&, int*)
  [13] __gnu_cxx::__normal_iterator<int const*, std::vector<int, std::allocator<int> > >::operator*() const [43] std::_Vector_base<int, std::allocator<int> >::~_Vector_base() [59] int* std::__copy_move_a<false, int const*, int*>(int const*, int const*, int*)
  [20] std::__new_allocator<int>::_M_max_size() const [44] std::__new_allocator<int>::deallocate(int*, unsigned long) [60] int* std::__copy_move_a1<false, int const*, int*>(int const*, int const*, int*)
  [30] std::__new_allocator<int>::max_size() const [45] std::__new_allocator<int>::allocate(unsigned long, void const*) [61] int* std::__copy_move_a2<false, int const*, int*>(int const*, int const*, int*)
  [31] std::initializer_list<int>::end() const [25] std::__new_allocator<int>::__new_allocator(std::__new_allocator<int> const&) [62] int* std::uninitialized_copy<int const*, int*>(int const*, int const*, int*)
  [32] std::initializer_list<int>::size() const [46] std::__new_allocator<int>::__new_allocator() [63] std::iterator_traits<int const*>::iterator_category std::__iterator_category<int const*>(int const* const&)
  [21] std::initializer_list<int>::begin() const [18] std::__new_allocator<int>::~__new_allocator() [64] int* std::__uninitialized_copy_a<int const*, int*, int>(int const*, int const*, int*, std::allocator<int>&)
  [22] std::vector<int, std::allocator<int> >::end() const [47] std::allocator_traits<std::allocator<int> >::deallocate(std::allocator<int>&, int*, unsigned long) [65] unsigned long const& std::min<unsigned long>(unsigned long const&, unsigned long const&)
  [33] std::vector<int, std::allocator<int> >::size() const [48] std::allocator_traits<std::allocator<int> >::allocate(std::allocator<int>&, unsigned long) [66] int* std::copy<int const*, int*>(int const*, int const*, int*)
  [23] std::vector<int, std::allocator<int> >::begin() const [49] std::allocator_traits<std::allocator<int> >::max_size(std::allocator<int> const&) [9] std::remove_reference<int&>::type&& std::move<int&>(int&)
  [24] std::allocator<int>::allocator(std::allocator<int> const&) [50] int* std::__uninitialized_copy<true>::__uninit_copy<int const*, int*>(int const*, int const*, int*) [14] std::enable_if<std::__and_<std::__not_<std::__is_tuple_like<int> >, std::is_move_constructible<int>, std::is_move_assignable<int> >::value, void>::type std::swap<int>(int&, int&)
  [34] std::allocator<int>::allocator() [51] std::vector<int, std::allocator<int> >::_S_max_size(std::allocator<int> const&) [67] void std::_Destroy<int*>(int*, int*)
  [16] std::allocator<int>::~allocator() [52] std::vector<int, std::allocator<int> >::_S_check_init_len(unsigned long, std::allocator<int> const&) [68] void std::_Destroy<int*, int>(int*, int*, std::allocator<int>&)
  [35] int* std::__copy_move<false, true, std::random_access_iterator_tag>::__copy_m<int>(int const*, int const*, int*) [53] void std::vector<int, std::allocator<int> >::_M_range_initialize<int const*>(int const*, int const*, std::forward_iterator_tag) [69] std::iterator_traits<int const*>::difference_type std::distance<int const*>(int const*, int const*)
  [36] void std::_Destroy_aux<true>::__destroy<int*>(int*, int*) [54] std::vector<int, std::allocator<int> >::vector(std::initializer_list<int>, std::allocator<int> const&)
