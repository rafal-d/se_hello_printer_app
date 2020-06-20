zmiana imienie na Rafal
bug w clasie --> funkcji def test_msg_with_output(self):
        rv = self.app.get('/?output=json')
        self.assertEqual(b' { "imie":"Natalia", "mgs":Hello World!"}', rv.data)

brak spacji po b'{
