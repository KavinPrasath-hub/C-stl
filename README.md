# C-stl
1)vector<int> arr
  - arr.begin() - first ele address,
  -arr.end() - last ele address+1,
  - arr.empty()- returns true if empty else false,
  - arr.clear() - clears all the element in arr,
  - sort(arr.begin(),arr.end())- ascending order,
  - sort(arr.begin(),arr.end(),greater<int>()) - descending order,
  - arr.rbegin(),arr.rend() - reverse iterators,
  - .cbegin,crbegin,cend,crend - constant iterators,
  - arr.push_back(),
  - arr.pop_back(),
  - arr.front() - first element refernce,
  - arr.back() - last element reference,
  - arr.insert(pos,data),
  - arr.insert(pos,arr),
  - arr.insert(arr2.begin(),arr2.begin()+2) - inserted until arr.begin()+1,
  - arr.erase(pos),
  - arr.erase(arr.begin()) - erases at begining,
  - arr.erase(arr.begin(),arr.end()-1) - erases from begining to end,
  - arr.resize(size) - if size incre - fills zero for new, else reduce upto n;
-2)forward_list(data_type) ll
  - implements singly linked list,
  - ll.push_front(),
  - ll.pop_front(),
  - ll.assign({n1,n2,n3}) - assign values to the linked list,
  - ll.assign(time, val) - assign repeated values to linked list,
  - ll.emplace_front(val) - no copying oocurs, similiar to push_front,
  - ll.insert_after(address, val or array)
  - ll.emplace_after(add,val),
  - ll.erase_after(add),
  - ll.erase_after(add1,add2) - removes from add1 to add2,
  - ll.clear(),
  - ll.empty(),
  - ll.reverse(),
  - ll.merge(ll2) - merges two sorted linked list,
  - ll.sort() -ascending order,
  - ll.sort(greater<int>()) - descending order,
  - ll.remove(val) - removes all the val,
  - ll.remove if ([](int x) {return condition})- removes val satisfying condition),
  - ll.splice_after(pos,ll2) - enters the ll after the pos,
  
