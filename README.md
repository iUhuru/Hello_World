# Hello_World
First_time
<p> This is me <p>
  
@pytest.mark.script
def test_parse():
    script = Script.parse(['python', '-c', "print('hello')"])
    assert script.command == 'python'
    assert script.args == ['-c', "print('hello')"], script


@pytest.mark.run
