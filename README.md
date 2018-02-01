for find instances ip with matched  "aws security group name" 
we should run:

perl json_parser.pl.tdy aws_security_group_name

Output is like this:
 perl json_parser.pl.tdy  web
172.22.160.91
prod-wed-server
172.10.19.13
prod-wed-server

Note script used aws cli tool (https://aws.amazon.com/cli/?sc_channel=PS&sc_campaign=acquisition_PH&sc_publisher=google&sc_medium=command_line_b&sc_content=aws_cli_e&sc_detail=aws%20cli&sc_category=command_line&sc_segment=165206230727&sc_matchtype=e&sc_country=UA&s_kwcid=AL!4422!3!165206230727!e!!g!!aws%20cli&ef_id=WarXRAAABITQxBwd:20180201153209:s)
