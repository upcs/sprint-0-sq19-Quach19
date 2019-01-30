//Michael Quach
language: node_js


test(‘add 7 + 1 to equal 8’, () => {
	expect(sum(7, 1)).toBe(8); //to test success
	expect(sum(7, 1)).toBe(9); //to test failure
});