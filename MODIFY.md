### 需要修改的bug记录在这里
1.  Action.events.emit('test', null);
     Store.on('events.test', data => {
                console.log('test', data)
     })
    emit null but receives [] in store