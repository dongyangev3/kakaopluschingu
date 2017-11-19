<?php
// content : 가사모 공식 홈페이지
use \kakao\Msg;
use \kakao\Msg\Message;
use \kakao\Keyboard;

echo new Msg(
        new Message(
                "가사모 홈페이지 입니다",
                NULL,
                array(
                        "/가사모 홈페이지",
                        "http://gaslove.creatorlink.net"
                )
        ),
        TRUE
);
