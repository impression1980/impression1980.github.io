---
layout: post
title:  "Basic Code Snippet"
date:   2021-02-01
author: mastermind
categories: Python_Study
---

## ajex 기본코드 

*GET

    function listing() {

        $.ajax({

            type: "GET",

            url: "/diary?sample_give=샘플데이터",

            data: {},

            success: function(response){

               alert(response['msg'])

            }

          })

      }

*POST
    function posting() {
        $.ajax({
            type: "POST",
            url: "/diary",
            data: { sample_give:'샘플데이터' },
            success: function(response){
                alert(response['msg'])
            }
          })
      }


