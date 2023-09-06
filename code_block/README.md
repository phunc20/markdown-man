- Highlight, e.g.
    - Cf. <https://retype.com/components/code-block/>
    - Lines 4 and 10
      ```python #4,10
      def test_should_delete_key_value_pair(hash_table):
      assert "hola" in hash_table
      assert "hello" in hash_table.values
      assert len(hash_table) == 100
  
      del hash_table["hola"]
  
      assert "hola" not in hash_table
      assert "hello" not in hash_table.values
      assert len(hash_table) == 100
      ```  
