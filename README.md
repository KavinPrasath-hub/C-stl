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
  
